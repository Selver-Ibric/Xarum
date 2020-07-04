<template>
  <div class="counters-section text-center">
    <b-container class="main-counters">
      <b-row class="justify-content-center">
        <b-col cols="12" md="4" class="column-with-img py-2 py-md-0">
          <div class="image-container">
            <img class="counter-image" src="~/assets/images/counters/counter-image-1.svg">
          </div>

          <div class="counter-value">
            71,186,492.99 <sup class="unit">XAUR</sup>
          </div>
          <div class="counter-label text-center">
            {{ $t('counters.supply') }}
          </div>
        </b-col>

        <b-col cols="12" md="4" class="column-with-img py-2 py-md-0">
          <div class="image-container">
            <img class="counter-image" src="~/assets/images/counters/counter-image-2.svg">
          </div>

          <div class="counter-value">
            820.11 <sup class="unit">%</sup>
          </div>
          <div class="counter-label text-center">
            {{ $t('counters.growth') }}
          </div>
        </b-col>

        <b-col cols="12" md="4" class="column-with-img py-2 py-md-0">
          <div class="image-container">
            <img class="counter-image" src="~/assets/images/counters/counter-image-3.svg">
          </div>

          <div class="counter-value">
            72,975.96 <sup class="unit">g</sup>
          </div>
          <div class="counter-label text-center">
            {{ $t('counters.vault') }}
          </div>
        </b-col>
      </b-row>

      <div class="text-right">
        <b-button v-b-toggle.collapse-1 variant="primary" class="counter-btn">
          <img class="counter-arrow-icon" src="~/assets/images/icons/counter-arrow.svg">
        </b-button>
      </div>
    </b-container>

    <b-collapse id="collapse-1" class="aditional-counters">
      <b-container class="aditional-counters-container">
        <b-row class="justify-content-center">
          <b-col cols="12" md="4" class="counter-column">
            <div class="counter-label text-center">
              {{ $t('counters.ratio') }}
            </div>
            <div class="counter-value">
              1000 <sup class="unit">XAUR</sup> = <span class="d-inline-block">1.02513772 <sup class="unit green-arrow-unit">g/gold</sup></span>
            </div>
          </b-col>

          <b-col cols="12" md="4" class="counter-column">
            <div class="counter-label text-center">
              {{ $t('counters.trading') }}
            </div>
            <div class="counter-value">
              13,907.66 <sup class="unit">$</sup>
            </div>
          </b-col>

          <b-col cols="12" md="4" class="counter-column">
            <div class="counter-label text-center">
              {{ $t('counters.holders') }}
            </div>
            <div class="counter-value">
              3,686 <sup class="unit">wallets</sup>
            </div>
          </b-col>

          <b-col cols="12" md="4" class="counter-column">
            <div class="counter-label text-center">
              {{ $t('counters.transactions') }}
            </div>
            <div class="counter-value">
              4
            </div>
          </b-col>

          <b-col cols="12" md="4" class="counter-column">
            <div class="counter-label text-center">
              {{ $t('counters.xaurums') }}
            </div>
            <div class="counter-value">
              2.0
            </div>
          </b-col>
        </b-row>
      </b-container>
    </b-collapse>
  </div>
</template>
