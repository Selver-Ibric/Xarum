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
            Brand
          </h1>

          <h3 class="sub-subtitle">
            Brand Policy
          </h3>

          <p>The brand policy of Xaurum is the presentation of it to the public in a way that makes it easy for people to recognize or identify. It is a combination of rules, procedures and guidelines on how Xaurum brand must be represented.</p>

          <div class="text-center">
            <a href="#" class="btn btn-primary btn-big">DOWNLOAD POLICY</a>
          </div>

          <h3 class="sub-subtitle">
            Brand Guidelines
          </h3>

          <p>Brand guidelines are a set of tools and rules on how to use branding elements. The guidelines are used by designers, writers, and anyone else using brand's elements like logo to create marketing or other materials.</p>

          <div class="text-center">
            <a href="/documents/Styleguide.pdf" target="_blank" class="btn btn-primary btn-big">DOWNLOAD GUIDELINES</a>
          </div>

          <h2 class="subtitle decoration-title2">
            LOGOS
          </h2>

          <h3 class="sub-subtitle">
            Xaurum Community
          </h3>

          <p>Here you can find Xaurum Community logos. Community is important part of Xaurum story and expands under and with different Masternode activities. When using the logos, please publish the following statement alongside: »This page/material is not official Xaurum account/promo material and do not in any way represent the views and policy of the Auresco Institute and Xaurum brand.«</p>

          <div class="text-center">
            <a href="/files/CommunityLogos.zip" target="_blank" download class="btn btn-primary btn-big">DOWNLOAD LOGOS</a>
          </div>

          <h3 class="sub-subtitle">
            Xaurum
          </h3>

          <p>Here you can find different official logos that can be used only with written permission of Auresco Institute.</p>

          <div class="text-center">
            <a href="/files/XaurumLogos.zip" target="_blank" download class="btn btn-primary btn-big">DOWNLOAD LOGOS</a>
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
