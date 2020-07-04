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
            {{ $t('whitepaper.title') }}
          </h1>

          <p>
            {{ $t('whitepaper.text1') }}
          </p>

          <div class="text-center detail-btn-container">
            <a href="/documents/Whitepaper.pdf" target="_blank" class="btn btn-big btn-primary">{{ $t('whitepaper.btn1Text') }}</a>
          </div>

          <p>
            You are also more than welcome to read The Treatise On Xaurum <a href="/documents/TreatiseOnXaurum.pdf" target="_blank">here</a>. The document was published June 22, 2016.
          </p>

          <div class="text-center">
            <a href="/documents/onepager.pdf" target="_blank" class="btn btn-big btn-primary">{{ $t('whitepaper.btn2Text') }}</a>
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
