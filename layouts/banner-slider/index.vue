<template>
  <div class="banner-slider-section position-relative">
    <div v-swiper:myImageSwiper="swiperOption" class="banner-slider">
      <div class="swiper-wrapper">
        <div class="swiper-slide">
          <img class="slide-img" src="~/assets/images/banner-slider/slider-image-1.jpg">

          <div class="slide-content">
            <b-container class="slide-container">
              <h1 class="slide-title">
                {{ $t('slider.slide1Title') }}
              </h1>

              <p class="slide-text">
                {{ $t('slider.slide1Text') }}
              </p>

              <div class="slide-actions">
                <nuxt-link :to="$t('slider.btn1Link')" class="btn btn-secondary btn-banner btn-big">
                  {{ $t('slider.btn1Text') }}
                </nuxt-link>

                <nuxt-link :to="$t('slider.btn2Link')" class="btn btn-primary btn-banner btn-big">
                  {{ $t('slider.btn2Text') }}
                </nuxt-link>
              </div>
            </b-container>
          </div>
        </div>

        <div class="swiper-slide">
          <img class="slide-img" src="~/assets/images/banner-slider/slider-image-2.jpg">

          <div class="slide-content">
            <b-container class="slide-container">
              <h1 class="slide-title">
                {{ $t('slider.slide2Title') }}
              </h1>

              <p class="slide-text">
                {{ $t('slider.slide2Text') }}
                <br>
                {{ $t('slider.xaurumText') }}
              </p>

              <div class="slide-actions">
                <nuxt-link :to="$t('slider.btn1Link')" class="btn btn-secondary btn-banner btn-big">
                  {{ $t('slider.btn1Text') }}
                </nuxt-link>

                <nuxt-link :to="$t('slider.btn2Link')" class="btn btn-primary btn-banner btn-big">
                  {{ $t('slider.btn2Text') }}
                </nuxt-link>
              </div>
            </b-container>
          </div>
        </div>

        <div class="swiper-slide">
          <img class="slide-img" src="~/assets/images/banner-slider/slider-image-3.jpg">

          <div class="slide-content">
            <b-container class="slide-container">
              <h1 class="slide-title">
                {{ $t('slider.slide3TitlePart1') }}
                <br>
                {{ $t('slider.slide3TitlePart2') }}
              </h1>

              <p class="slide-text">
                {{ $t('slider.slide3Text') }}
                <br>
                {{ $t('slider.xaurumText') }}
              </p>

              <div class="slide-actions">
                <nuxt-link :to="$t('slider.btn1Link')" class="btn btn-secondary btn-banner btn-big">
                  {{ $t('slider.btn1Text') }}
                </nuxt-link>

                <nuxt-link :to="$t('slider.btn2Link')" class="btn btn-primary btn-banner btn-big">
                  {{ $t('slider.btn2Text') }}
                </nuxt-link>
              </div>
            </b-container>
          </div>
        </div>

        <div class="swiper-slide">
          <img class="slide-img" src="~/assets/images/banner-slider/slider-image-4.jpg">

          <div class="slide-content">
            <b-container class="slide-container">
              <h1 class="slide-title">
                {{ $t('slider.slide4Title') }}
              </h1>

              <p class="slide-text">
                {{ $t('slider.slide4Text') }}
                <br>
                {{ $t('slider.xaurumText') }}
              </p>

              <div class="slide-actions">
                <nuxt-link :to="$t('slider.btn1Link')" class="btn btn-secondary btn-banner btn-big">
                  {{ $t('slider.btn1Text') }}
                </nuxt-link>

                <nuxt-link :to="$t('slider.btn2Link')" class="btn btn-primary btn-banner btn-big">
                  {{ $t('slider.btn2Text') }}
                </nuxt-link>
              </div>
            </b-container>
          </div>
        </div>
      </div>
    </div>

    <div class="swiper-pagination swiper-pagination-bullets swiper-pagination-clickable" />
  </div>
</template>

<script>
export default {
  data () {
    return {
      loading: true,
      swiperOption: {
        // effect: 'fade',
        autoplay: {
          delay: 10000,
          disableOnInteraction: false
        },
        clickable: true,
        autoHeight: true,
        loop: true,
        slidesPerView: 1,
        centeredSlides: true,
        spaceBetween: 0,
        pagination: {
          el: '.swiper-pagination',
          clickable: true
        }
      }
    }
  }
}
</script>
