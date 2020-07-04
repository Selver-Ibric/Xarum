<template>
  <div class="footer">
    <b-container>
      <b-row>
        <b-col cols="12" md="6" lg="2" xl="3" class="footer-logo-col text-center text-lg-left">
          <logo />
        </b-col>

        <b-col cols="12" md="6" lg="5" xl="4" class="footer-info-col">
          <info id="footer-contact" />
        </b-col>

        <b-col cols="12" lg="5" class="footer-media-col">
          <social-media />

          <p class="copyright-text text-left text-md-center text-lg-right">
            © {{ $t('footer.copyright') }}
          </p>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
import Logo from '~/components/footer/logo.vue'
import Info from '~/components/footer/info.vue'
import SocialMedia from '~/components/footer/social-media.vue'

export default {
  components: {
    Logo,
    Info,
    SocialMedia
  }
}
</script>
