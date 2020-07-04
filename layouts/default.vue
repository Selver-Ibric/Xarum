<template>
  <div>
    <loading-content :class="{ 'not-active' : !isLoading}" />

    <div class="main-page-wrapper">
      <app-header />

      <nuxt />

      <app-footer />
    </div>

    <!-- <CookieControl /> -->
  </div>
</template>

<script>
import LoadingContent from '~/layouts/loading/index.vue'
import AppHeader from '~/layouts/header/index.vue'
import AppFooter from '~/layouts/footer/index.vue'

export default {
  components: {
    LoadingContent,
    AppHeader,
    AppFooter
  },
  data () {
    return {
      isLoading: true
    }
  },
  mounted () {
    setTimeout(() => {
      this.isLoading = false
    }, 2500)
  }
}
</script>
