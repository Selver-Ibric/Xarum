<template>
  <div class="header" :class="{ 'hidden-header': !showHeader }">
    <top-bar />

    <b-container>
      <b-row class="header-row align-items-center">
        <b-col cols="8" lg="auto" class="logo-column">
          <logo />
        </b-col>

        <b-col class="navigation-column">
          <navigation class="d-none d-lg-block" />

          <mobile-navigation class="d-lg-none" />
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
import TopBar from '~/components/header/top-bar.vue'
import Logo from '~/components/header/logo.vue'
import Navigation from '~/components/header/navigation.vue'
import MobileNavigation from '~/components/header/mobile-navigation.vue'

export default {
  components: {
    TopBar,
    Logo,
    Navigation,
    MobileNavigation
  },
  data () {
    return {
      showHeader: true,
      lastScrollPosition: 0,
      scrollValue: 0
    }
  },
  mounted () {
    this.lastScrollPosition = window.pageYOffset
    window.addEventListener('scroll', this.onScroll)
    const viewportMeta = document.createElement('meta')
    viewportMeta.name = 'viewport'
    viewportMeta.content = 'width=device-width, initial-scale=1'
    document.head.appendChild(viewportMeta)
  },
  beforeDestroy () {
    window.removeEventListener('scroll', this.onScroll)
  },
  methods: {
    onScroll () {
      if (window.pageYOffset < 0) {
        return
      }
      if (Math.abs(window.pageYOffset - this.lastScrollPosition) < 50) {
        return
      }
      this.showHeader = window.pageYOffset < this.lastScrollPosition
      this.lastScrollPosition = window.pageYOffset
    }
  }
}
</script>
