<template>
  <div class="page-wrapper">
    <app-banner-slider />
    <app-counters />
    <app-graphs />
    <app-partners />
    <app-how-it-works />
    <app-print-banner />
    <app-why-xaurum />
    <app-here-to-help />
    <app-how-to-buy />
    <app-team />
  </div>
</template>

<script>
import AppBannerSlider from '~/layouts/banner-slider/index.vue'
import AppCounters from '~/layouts/counters/index.vue'
import AppGraphs from '~/layouts/graphs/index.vue'
import AppPartners from '~/layouts/partners/index.vue'
import AppHowItWorks from '~/layouts/how-it-works/index.vue'
import AppPrintBanner from '~/layouts/print-banner/index.vue'
import AppWhyXaurum from '~/layouts/why-xaurum/index.vue'
import AppHereToHelp from '~/layouts/here-to-help/index.vue'
import AppHowToBuy from '~/layouts/how-to-buy/index.vue'
import AppTeam from '~/layouts/team/index.vue'

export default {
  components: {
    AppBannerSlider,
    AppCounters,
    AppGraphs,
    AppPartners,
    AppHowItWorks,
    AppPrintBanner,
    AppWhyXaurum,
    AppHereToHelp,
    AppHowToBuy,
    AppTeam
  }
}
</script>
