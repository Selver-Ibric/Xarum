<template>
  <b-container class="exchange-container">
    <h1 class="exchanges-title text-center">
      {{ $t('howToBuy.exchangesTitle') }}
    </h1>

    <b-row class="align-items-center">
      <b-col cols="12" md="4" class="exchange-column">
        <a href="https://mercatox.com/" target="_blank">
          <img class="img-fluid exchange-img opacity-50" src="~/assets/images/exchanges/mercatox.png">
        </a>
      </b-col>

      <b-col cols="12" md="4" class="exchange-column">
        <a href="https://hitbtc.com/" target="_blank">
          <img class="img-fluid exchange-img" src="~/assets/images/exchanges/hitBTC.png">
        </a>
      </b-col>

      <b-col cols="12" md="4" class="exchange-column">
        <a href="https://www.livecoin.net/" target="_blank">
          <img class="img-fluid exchange-img" src="~/assets/images/exchanges/liveCoin.png">
        </a>
      </b-col>

      <b-col cols="12" md="4" class="exchange-column">
        <a href="https://c-cex.com/" target="_blank">
          <img class="img-fluid exchange-img" src="~/assets/images/exchanges/ccex.png">
        </a>
      </b-col>

      <b-col cols="12" md="4" class="exchange-column">
        <a href="https://radarrelay.com/" target="_blank">
          <img class="img-fluid exchange-img opacity-50" src="~/assets/images/exchanges/radar.png">
        </a>
      </b-col>

      <b-col cols="12" md="4" class="exchange-column">
        <a href="https://etherdelta.com/#XAUR-ETH" target="_blank">
          <img class="img-fluid exchange-img" src="~/assets/images/exchanges/etherDelta.png">
        </a>
      </b-col>
    </b-row>
  </b-container>
</template>
