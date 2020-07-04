<template>
  <b-container class="how-it-works-tabs">
    <b-tabs content-class="">
      <b-tab title="01" active>
        <div>
          <img class="tab-img" src="~/assets/images/tabs/tab-1.svg">

          <h1 class="tab-title">
            {{ $t('howItWorks.tab1Title') }}
          </h1>

          <p class="tab-text">
            {{ $t('howItWorks.tab1Text') }}
          </p>
        </div>
      </b-tab>

      <b-tab title="02">
        <div>
          <img class="tab-img" src="~/assets/images/tabs/tab-2.svg">

          <h1 class="tab-title">
            {{ $t('howItWorks.tab2Title') }}
          </h1>

          <p class="tab-text">
            {{ $t('howItWorks.tab2Text') }}
          </p>
        </div>
      </b-tab>

      <b-tab title="03">
        <div>
          <img class="tab-img" src="~/assets/images/tabs/tab-3.svg">

          <h1 class="tab-title">
            {{ $t('howItWorks.tab3Title') }}
          </h1>

          <p class="tab-text">
            {{ $t('howItWorks.tab3Text') }}
          </p>
        </div>
      </b-tab>

      <b-tab title="04">
        <div>
          <img class="tab-img" src="~/assets/images/tabs/tab-4.svg">

          <h1 class="tab-title">
            {{ $t('howItWorks.tab4Title') }}
          </h1>

          <p class="tab-text">
            {{ $t('howItWorks.tab4Text') }}
          </p>
        </div>
      </b-tab>

      <b-tab title="05">
        <div>
          <img class="tab-img" src="~/assets/images/tabs/tab-5.svg">

          <h1 class="tab-title">
            {{ $t('howItWorks.tab5Title') }}
          </h1>

          <p class="tab-text">
            {{ $t('howItWorks.tab5Text') }}
          </p>
        </div>
      </b-tab>

      <b-tab title="06">
        <div>
          <img class="tab-img" src="~/assets/images/tabs/tab-6.svg">

          <h1 class="tab-title">
            {{ $t('howItWorks.tab6Title') }}
          </h1>

          <p class="tab-text">
            {{ $t('howItWorks.tab6Text') }}
          </p>
        </div>
      </b-tab>

      <b-tab title="07">
        <div>
          <img class="tab-img" src="~/assets/images/tabs/tab-7.svg">

          <h1 class="tab-title">
            {{ $t('howItWorks.tab7Title') }}
          </h1>

          <p class="tab-text">
            {{ $t('howItWorks.tab7Text') }}
          </p>
        </div>
      </b-tab>
    </b-tabs>

    <div class="tabs-action text-center text-md-left">
      <a href="#why-xaurum" class="btn btn-primary btn-banner">{{ $t('howItWorks.btnText') }}</a>
    </div>
  </b-container>
</template>
