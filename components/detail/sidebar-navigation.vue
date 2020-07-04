<template>
  <div class="sidebar-container">
    <ul class="list-unstyled sidebar-list">
      <li class="sidebar-item">
        <nuxt-link to="whitepaper" class="sidebar-link" :class="{ active : this.$route.path.includes('whitepaper')}">
          {{ $t('sidebar.whitepaper') }}
        </nuxt-link>
      </li>
      <li class="sidebar-item">
        <nuxt-link to="melt" class="sidebar-link" :class="{ active : this.$route.path.includes('melt')}">
          Melt
        </nuxt-link>
      </li>
      <li class="sidebar-item">
        <nuxt-link to="audit" class="sidebar-link" :class="{ active : this.$route.path.includes('audit')}">
          {{ $t('sidebar.audit') }}
        </nuxt-link>
      </li>
      <li class="sidebar-item">
        <nuxt-link to="legal" class="sidebar-link" :class="{ active : this.$route.path.includes('legal')}">
          Legal
        </nuxt-link>
      </li>
      <li class="sidebar-item">
        <nuxt-link to="calculator" class="sidebar-link" :class="{ active : this.$route.path.includes('calculator')}">
          Calculator
        </nuxt-link>
      </li>
      <li class="sidebar-item">
        <nuxt-link to="brand" class="sidebar-link" :class="{ active : this.$route.path.includes('brand')}">
          Brand
        </nuxt-link>
      </li>
      <li class="sidebar-item">
        <nuxt-link to="extras" class="sidebar-link" :class="{ active : this.$route.path.includes('extras')}">
          Extras
        </nuxt-link>
      </li>
    </ul>
  </div>
</template>
