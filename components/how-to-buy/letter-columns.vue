<template>
  <b-container class="buy-info-container">
    <b-row class="text-center justify-content-around buy-info-row">
      <b-col cols="12" md="6" lg="4" class="buy-info-column">
        <div class="image-container">
          <img class="img-fluid buy-img" src="~/assets/images/buy/a.svg">
          <img class="img-fluid buy-img-full" src="~/assets/images/buy/a-fill.svg">
        </div>

        <h1 class="title">
          {{ $t('howToBuy.column1Title') }}
        </h1>
        <p class="buy-info-text">
          {{ $t('howToBuy.column1Text') }}
        </p>
      </b-col>

      <b-col cols="12" md="6" lg="4" class="buy-info-column second-column">
        <div class="image-container">
          <img class="img-fluid buy-img" src="~/assets/images/buy/b.svg">
          <img class="img-fluid buy-img-full" src="~/assets/images/buy/b-fill.svg">
        </div>

        <h1 class="title">
          {{ $t('howToBuy.column2Title') }}
        </h1>
        <p class="buy-info-text">
          {{ $t('howToBuy.column2Text') }}
        </p>
      </b-col>

      <b-col cols="12" md="6" lg="4" class="buy-info-column">
        <div class="image-container">
          <img class="img-fluid buy-img" src="~/assets/images/buy/c.svg">
          <img class="img-fluid buy-img-full" src="~/assets/images/buy/c-fill.svg">
        </div>

        <h1 class="title">
          {{ $t('howToBuy.column3Title') }}
        </h1>
        <p class="buy-info-text">
          {{ $t('howToBuy.column3Text') }}
        </p>
      </b-col>
    </b-row>
  </b-container>
</template>
