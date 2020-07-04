<template>
  <b-container class="top-bar">
    <ul class="list-unstyled d-flex justify-content-end lang-list">
      <li class="item-lang">
        <nuxt-link :to="switchLocalePath('en')" class="lang-link">
          EN
        </nuxt-link>
      </li>
      <li class="item-lang">
        <nuxt-link :to="switchLocalePath('de')" class="lang-link">
          DE
        </nuxt-link>
      </li>
      <li class="item-lang">
        <nuxt-link :to="switchLocalePath('es')" class="lang-link">
          ES
        </nuxt-link>
      </li>
      <li class="item-lang">
        <nuxt-link :to="switchLocalePath('pt')" class="lang-link">
          PT
        </nuxt-link>
      </li>
      <li class="item-lang">
        <nuxt-link :to="switchLocalePath('si')" class="lang-link">
          SI
        </nuxt-link>
      </li>
    </ul>
  </b-container>
</template>
