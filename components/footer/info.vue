<template>
  <div class="footer-info">
    <div class="list-item">
      <div class="icon float-left">
        <img class="logo-img" src="~/assets/images/icons/pin-icon.svg" alt="">
      </div>

      <div class="location-info">
        Crystal Palace, BTC City, <br>
        Ameriška ulica 8, Ljubljana, Slovenia
      </div>
    </div>

    <div class="list-item">
      <div class="icon float-left">
        <img class="logo-img" src="~/assets/images/icons/envelope-icon.svg" alt="">
      </div>

      <a class="info-link" href="mailto:info@xaurum.org">info@xaurum.org</a>
    </div>

    <div class="list-item">
      <div class="icon float-left">
        <img class="logo-img" src="~/assets/images/icons/globus-icon.svg" alt="">
      </div>

      <a class="info-link" href="www.xaurum.org">www.xaurum.org</a>
    </div>

    <ul class="list-unstyled d-flex info-list">
      <li class="info-list--item">
        <a class="info-list--link pl-0" href="/documents/Privacy_policy.pdf" target="_blank">Privacy policy</a>
      </li>
      <li class="info-list--item">
        <a class="info-list--link" href="/documents/Terms_of_use.pdf" target="_blank">Terms of use</a>
      </li>
      <li class="info-list--item">
        <!-- <a class="info-list--link" href="#">Cookie settings</a> -->
        <nuxt-link :to="$t('footer.cookiesLink')" class="info-list--link">
          Cookie settings
        </nuxt-link>
      </li>
    </ul>
  </div>
</template>
