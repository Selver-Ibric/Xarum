<template>
  <div id="how-to-buy" class="how-to-buy-section">
    <h1 class="decoration-title text-center">
      {{ $t('howToBuy.title') }}
    </h1>

    <p class="text text-center">
      {{ $t('howToBuy.text') }}
    </p>

    <letter-columns />

    <div class="text-center px-3">
      <a href="https://www.xaurum.pro/" target="_blank" class="btn btn-primary btn-big">{{ $t('howToBuy.btn1Text') }}</a>
    </div>

    <exchange />

    <div class="text-center mt-5 px-3">
      <a href="https://payment.xaurum.io/" target="_blank" class="btn btn-primary btn-big">{{ $t('howToBuy.btn2Text') }}</a>
    </div>
  </div>
</template>

<script>
import Exchange from '~/components/how-to-buy/exchange.vue'
import LetterColumns from '~/components/how-to-buy/letter-columns.vue'

export default {
  components: {
    Exchange,
    LetterColumns
  }
}
</script>
