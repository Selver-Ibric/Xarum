<template>
  <div class="navigation-container">
    <ul class="list-unstyled d-flex navigation-list">
      <li class="navigation-item">
        <nuxt-link :to="$t('navigation.link1')" class="navigation-link">
          {{ $t('navigation.link1Text') }}
        </nuxt-link>
      </li>

      <li class="navigation-item">
        <nuxt-link :to="$t('navigation.link2')" class="navigation-link">
          {{ $t('navigation.link2Text') }}
        </nuxt-link>
      </li>

      <li class="navigation-item">
        <nuxt-link :to="$t('navigation.link3')" class="navigation-link">
          {{ $t('navigation.link3Text') }}
        </nuxt-link>
      </li>

      <li class="navigation-item">
        <nuxt-link :to="$t('navigation.link4')" class="navigation-link" :class="{ active : this.$route.path.includes('details')}">
          {{ $t('navigation.link4Text') }}
        </nuxt-link>
      </li>
    </ul>
  </div>
</template>
