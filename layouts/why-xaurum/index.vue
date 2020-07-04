<template>
  <div id="why-xaurum" class="why-xaurum-section">
    <h1 class="why-xaurum-title decoration-title text-center">
      {{ $t('whyXaurum.title') }}
    </h1>
    <h2 class="why-xaurum-subtitle text-center text-uppercase">
      {{ $t('whyXaurum.subtitle') }}
    </h2>
    <h3 class="why-xaurum-description">
      {{ $t('whyXaurum.description') }}
    </h3>

    <b-container>
      <b-row class="why-xaurum-row">
        <b-col cols="12" md="6" lg="3" class="why-xaurum-column">
          <h1 class="title decoration-title2">
            {{ $t('whyXaurum.column1Title') }}
          </h1>

          <p class="description">
            {{ $t('whyXaurum.column1Text') }}
          </p>
        </b-col>

        <b-col cols="12" md="6" lg="3" class="why-xaurum-column">
          <h1 class="title decoration-title2">
            {{ $t('whyXaurum.column2Title') }}
          </h1>

          <p class="description">
            {{ $t('whyXaurum.column2Text') }}
          </p>
        </b-col>

        <b-col cols="12" md="6" lg="3" class="why-xaurum-column">
          <h1 class="title decoration-title2">
            {{ $t('whyXaurum.column3Title') }}
          </h1>

          <p class="description">
            {{ $t('whyXaurum.column3Text') }}
          </p>
        </b-col>

        <b-col cols="12" md="6" lg="3" class="why-xaurum-column">
          <h1 class="title decoration-title2">
            {{ $t('whyXaurum.column4Title') }}
          </h1>

          <p class="description">
            {{ $t('whyXaurum.column4Text') }}
          </p>
        </b-col>
      </b-row>

      <div class="quote-squared">
        {{ $t('whyXaurum.quote') }}
      </div>
    </b-container>
  </div>
</template>
