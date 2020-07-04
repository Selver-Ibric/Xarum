<template>
  <div class="text-right">
    <button class="menu-btn" @click="toggleMenu">
      <div class="menu-icon" :class="{ active : openMenu}">
        <span class="menu-bar-1" />
        <span class="menu-bar-2" />
        <span class="menu-bar-3" />
      </div>
    </button>

    <div class="mobile-menu position-fixed" :class="{ active : openMenu}">
      <ul class="list-unstyled d-flex justify-content-center mobile-lang-list">
        <li class="mobile-item-lang">
          <nuxt-link :to="switchLocalePath('en')" class="mobile-lang-link">
            EN
          </nuxt-link>
        </li>
        <li class="mobile-item-lang">
          <nuxt-link :to="switchLocalePath('de')" class="mobile-lang-link">
            DE
          </nuxt-link>
        </li>
        <li class="mobile-item-lang">
          <nuxt-link :to="switchLocalePath('es')" class="mobile-lang-link">
            ES
          </nuxt-link>
        </li>
        <li class="mobile-item-lang">
          <nuxt-link :to="switchLocalePath('pt')" class="mobile-lang-link">
            PT
          </nuxt-link>
        </li>
        <li class="mobile-item-lang mr-0">
          <nuxt-link :to="switchLocalePath('si')" class="mobile-lang-link">
            SI
          </nuxt-link>
        </li>
      </ul>

      <ul class="list-unstyled d-flex flex-column text-center">
        <li class="menu-item text-center" @click="toggleMenu">
          <nuxt-link :to="$t('navigation.link1')" class="menu-link">
            {{ $t('navigation.link1Text') }}
          </nuxt-link>
        </li>

        <li class="menu-item text-center" @click="toggleMenu">
          <nuxt-link :to="$t('navigation.link2')" class="menu-link">
            {{ $t('navigation.link2Text') }}
          </nuxt-link>
        </li>

        <li class="menu-item text-center" @click="toggleMenu">
          <nuxt-link :to="$t('navigation.link3')" class="menu-link">
            {{ $t('navigation.link3Text') }}
          </nuxt-link>
        </li>

        <li class="menu-item text-center" @click="toggleMenu">
          <nuxt-link :to="$t('navigation.link4')" class="menu-link">
            {{ $t('navigation.link4Text') }}
          </nuxt-link>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      openMenu: false
    }
  },
  methods: {
    toggleMenu () {
      this.openMenu = !this.openMenu
    }
  }
}
</script>
