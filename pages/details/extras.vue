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
            Extras
          </h1>

          <p class="text-center">
            Here you can find and download wallpapers for mobile phones & PC's.
          </p>

          <div class="text-center detail-btn-container btns">
            <a href="/files/XaurumWallpapers.zip" download target="_blank" class="btn btn-big btn-primary">DOWNLOAD FOR DESKTOP</a>
            <a href="/files/XaurumWallpapersMobile.zip" download target="_blank" class="btn btn-big btn-primary">DOWNLOAD FOR MOBILE</a>
          </div>

          <h3 class="sub-subtitle mb-3 text-center">
            Desktop
          </h3>

          <b-row class="wallpapers justify-content-center">
            <b-col cols="12" md="6" lg="4" class="wallpaper-desktop">
              <img class="wallpaper-img img-fluid" src="~/assets/images/extras/desktop/wallpaper-1.jpeg">
            </b-col>
            <b-col cols="12" md="6" lg="4" class="wallpaper-desktop">
              <img class="wallpaper-img img-fluid" src="~/assets/images/extras/desktop/wallpaper-2.jpeg">
            </b-col>
            <b-col cols="12" md="6" lg="4" class="wallpaper-desktop">
              <img class="wallpaper-img img-fluid" src="~/assets/images/extras/desktop/wallpaper-3.jpeg">
            </b-col>

            <b-col cols="12" md="6" lg="4" class="wallpaper-desktop">
              <img class="wallpaper-img img-fluid" src="~/assets/images/extras/desktop/wallpaper-4.jpeg">
            </b-col>
            <b-col cols="12" md="6" lg="4" class="wallpaper-desktop">
              <img class="wallpaper-img img-fluid" src="~/assets/images/extras/desktop/wallpaper-5.jpeg">
            </b-col>
            <b-col cols="12" md="6" lg="4" class="wallpaper-desktop">
              <img class="wallpaper-img img-fluid" src="~/assets/images/extras/desktop/wallpaper-6.jpeg">
            </b-col>

            <b-col cols="12" md="6" lg="4" class="wallpaper-desktop">
              <img class="wallpaper-img img-fluid" src="~/assets/images/extras/desktop/wallpaper-7.jpeg">
            </b-col>
            <b-col cols="12" md="6" lg="4" class="wallpaper-desktop">
              <img class="wallpaper-img img-fluid" src="~/assets/images/extras/desktop/wallpaper-8.jpeg">
            </b-col>
            <b-col cols="12" md="6" lg="4" class="wallpaper-desktop">
              <img class="wallpaper-img img-fluid" src="~/assets/images/extras/desktop/wallpaper-9.jpeg">
            </b-col>

            <b-col cols="12" md="6" lg="4" class="wallpaper-desktop">
              <img class="wallpaper-img img-fluid" src="~/assets/images/extras/desktop/wallpaper-10.jpeg">
            </b-col>
            <b-col cols="12" md="6" lg="4" class="wallpaper-desktop">
              <img class="wallpaper-img img-fluid" src="~/assets/images/extras/desktop/wallpaper-11.jpeg">
            </b-col>
            <b-col cols="12" md="6" lg="4" class="wallpaper-desktop">
              <img class="wallpaper-img img-fluid" src="~/assets/images/extras/desktop/wallpaper-12.jpeg">
            </b-col>
          </b-row>

          <h3 class="sub-subtitle mb-3 text-center">
            Mobile
          </h3>

          <b-row class="wallpapers justify-content-center">
            <b-col cols="12" md="6" lg="4" xl="3" class="wallpaper-mobile text-center">
              <img class="wallpaper-img h-100" src="~/assets/images/extras/mobile/wallpaper-1.jpeg">
            </b-col>
            <b-col cols="12" md="6" lg="4" xl="3" class="wallpaper-mobile text-center">
              <img class="wallpaper-img h-100" src="~/assets/images/extras/mobile/wallpaper-2.jpeg">
            </b-col>
            <b-col cols="12" md="6" lg="4" xl="3" class="wallpaper-mobile text-center">
              <img class="wallpaper-img h-100" src="~/assets/images/extras/mobile/wallpaper-3.jpeg">
            </b-col>

            <b-col cols="12" md="6" lg="4" xl="3" class="wallpaper-mobile text-center">
              <img class="wallpaper-img h-100" src="~/assets/images/extras/mobile/wallpaper-4.jpeg">
            </b-col>
            <b-col cols="12" md="6" lg="4" xl="3" class="wallpaper-mobile text-center">
              <img class="wallpaper-img h-100" src="~/assets/images/extras/mobile/wallpaper-5.jpeg">
            </b-col>
            <b-col cols="12" md="6" lg="4" xl="3" class="wallpaper-mobile text-center">
              <img class="wallpaper-img h-100" src="~/assets/images/extras/mobile/wallpaper-6.jpeg">
            </b-col>

            <b-col cols="12" md="6" lg="4" xl="3" class="wallpaper-mobile text-center">
              <img class="wallpaper-img h-100" src="~/assets/images/extras/mobile/wallpaper-7.jpeg">
            </b-col>
            <b-col cols="12" md="6" lg="4" xl="3" class="wallpaper-mobile text-center">
              <img class="wallpaper-img h-100" src="~/assets/images/extras/mobile/wallpaper-8.jpeg">
            </b-col>
            <b-col cols="12" md="6" lg="4" xl="3" class="wallpaper-mobile text-center">
              <img class="wallpaper-img h-100" src="~/assets/images/extras/mobile/wallpaper-9.jpeg">
            </b-col>

            <b-col cols="12" md="6" lg="4" xl="3" class="wallpaper-mobile text-center">
              <img class="wallpaper-img h-100" src="~/assets/images/extras/mobile/wallpaper-10.jpeg">
            </b-col>
            <b-col cols="12" md="6" lg="4" xl="3" class="wallpaper-mobile text-center">
              <img class="wallpaper-img h-100" src="~/assets/images/extras/mobile/wallpaper-11.jpeg">
            </b-col>
            <b-col cols="12" md="6" lg="4" xl="3" class="wallpaper-mobile text-center">
              <img class="wallpaper-img h-100" src="~/assets/images/extras/mobile/wallpaper-12.jpeg">
            </b-col>
          </b-row>
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
