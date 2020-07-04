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
          <h2 class="subtitle decoration-title2 cookie-title">
            Cookies
          </h2>

          <p>Xaurum collects information, which may include personal data, from your browser when you use our Site. We use a variety of methods, such as cookies and pixel tags to collect this information, which may include your (i) IP-address; (ii) unique cookie identifier, cookie information and information on whether your device has software to access certain features; (iii) unique device identifier and device type; (iv) domain, browser type and language, (v) operating system and system settings; (vi) country and time zone; (vii) previously visited websites; (viii) information about your interaction with our Sites such as click behavior, purchases and indicated preferences; and (ix) access times and referring URLs.</p>

          <p>Third parties may also collect information via Sites through cookies, third party plug-ins and widgets. These third parties collect data directly from your web browser and the processing of this data is subject to their own privacy policies.</p>

          <p>We use cookies and pixel tags to track our customers’ usage of the Site and to understand our customers’ preferences (such as country and language choices). This enables us to provide services to our customers and improve their online experience. We also use cookies and pixel tags to obtain aggregate data about site traffic and site interaction, to identify trends and obtain statistics so that we can improve our Site. There are generally three categories of cookies used on our Site:</p>

          <p>Functional: These cookies are required for basic site functionality and are therefore always enabled. These include cookies that allow you to be remembered as you explore our Site within a single session or, if you request, from session to session. They help make the shopping cart and checkout process possible as well as assist in security issues and conforming to regulations.</p>

          <p>Performance: These cookies allow us to improve our Site’s functionality by tracking usage. In some cases, these cookies improve the speed with which we can process your request and allow us to remember site preferences you have selected. Refusing these cookies may result in poorlytailored recommendations and slow site performance.</p>

          <p>Social media and Advertising: Social media cookies offer the possibility to connect you to your social networks and share content from our Site through social media. Advertising cookies (of third parties) collect information to help better tailor advertising to your interests, both within and beyond our Site. In some cases, these cookies involve the processing of your personal data. Refusing these cookies may result in seeing advertising that is not as relevant to you or you not being able to link effectively with Facebook, Twitter, or other social networks and/or not allowing you to share content on social media.</p>

          <p>You can always change your preference by visiting the "Cookie Settings" at the bottom of each page of our Sites.</p>

          <p>For a comprehensive and up-to-date summary of every third-party accessing your web browser, we recommend installing a web browser plugin built for this purpose. You can also choose to have your computer warn you each time a cookie is being sent, or you can choose to turn off all cookies. You do this through your browser settings on each browser and device that you use. Each browser is a little different, so look at your browser Help menu to learn the correct way to modify your cookies. If you turn cookies off, you may not have access to many features that make our Sites and Apps more efficient and some of our services will not function properly.</p>

          <h2 class="subtitle decoration-title2">
            SETTINGS
          </h2>
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
