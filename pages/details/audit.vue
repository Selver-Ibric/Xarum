<template>
  <div class="page-wrapper">
    <div class="text-center breadcrumb-custom">
      {{ $t('detailTitle') }}
    </div>

    <b-container>
      <b-row class="flex-column-reverse flex-md-row">
        <b-col cols="12" md="3" class="sidebar-column">
          <sidebar-navigation />
        </b-col>

        <b-col cols="12" md="9" class="detail-content">
          <h1 class="text-center decoration-title detail-page-title">
            {{ $t('audit.title') }}
          </h1>

          <h2 class="subtitle decoration-title2">
            {{ $t('audit.subtitle1') }}
          </h2>

          <p>
            {{ $t('audit.text1') }}
          </p>
          <p>
            {{ $t('audit.text2') }}
          </p>
          <p>
            {{ $t('audit.text3') }}
          </p>
          <p>
            {{ $t('audit.text4') }}
          </p>

          <div class="text-center detail-btn-container btns">
            <a href="/documents/PWC-SLO.pdf" target="_blank" class="btn btn-big btn-primary">{{ $t('audit.btn1Text1') }} <div class="btn-seconda-text">{{ $t('audit.btn1Text2') }}</div></a>
            <a href="/documents/PWC-ENGLISH.pdf" target="_blank" class="btn btn-big btn-primary">{{ $t('audit.btn2Text1') }} <div class="btn-seconda-text">{{ $t('audit.btn2Text2') }}</div></a>
          </div>

          <h2 class="subtitle decoration-title2">
            {{ $t('audit.subtitle2') }}
          </h2>

          <p>
            {{ $t('audit.text5') }}
          </p>
          <p>
            {{ $t('audit.text6') }}
          </p>
          <p>
            {{ $t('audit.text7') }}
          </p>

          <div class="text-center detail-btn-container btns">
            <a href="/documents/Statement-1.pdf" target="_blank" class="btn btn-big btn-primary">{{ $t('audit.btn3Text') }}</a>
            <a href="/documents/Statement-2.pdf" target="_blank" class="btn btn-big btn-primary">{{ $t('audit.btn4Text') }}</a>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
import SidebarNavigation from '~/components/detail/sidebar-navigation.vue'

export default {
  components: {
    SidebarNavigation
  }
}
</script>
