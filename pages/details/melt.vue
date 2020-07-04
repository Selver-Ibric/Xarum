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
            XAURUM MELT
          </h1>

          <h2 class="subtitle decoration-title2">
            Recieve 999.9 LBMA Certified Gold Anywhere In The World
          </h2>

          <p>
            Melting exchanges Xaurum for gold according to the coinage ratio at the time of melting.
          </p>
          <p>
            If you decide to melt please fill out this form.
          </p>

          <form id="formMelt" novalidate="novalidate" autocomplete="off" class="melt-form">
            <div class="field">
              <input type="number" name="quantity">
              <label class="input-label" for="quantity"><span>Quantity (g)</span></label>

              <div class="error-message">
                The quantity field is required.
              </div>
            </div>

            <div class="field">
              <input type="email" name="email">
              <label class="input-label" for="email"><span>Email</span></label>
            </div>

            <b-row>
              <b-col cols="12" md="2">
                <div class="field select-field">
                  <select name="title">
                    <option value="Mr.">
                      Mr.
                    </option>
                    <option value="Mrs.">
                      Mrs.
                    </option>
                    <option value="Miss">
                      Miss
                    </option>
                  </select>
                </div>
              </b-col>

              <b-col cols="12" md="5">
                <div class="field">
                  <input type="text" name="firstName">
                  <label class="input-label" for="firstName"><span>First Name</span></label>
                </div>
              </b-col>

              <b-col cols="12" md="5">
                <div class="field">
                  <input type="text" name="lastName">
                  <label class="input-label" for="lastName"><span>Last Name</span></label>
                </div>
              </b-col>
            </b-row>

            <div class="field">
              <input type="text" name="streetAddress1">
              <label class="input-label" for="streetAddress1"><span>Street Address</span></label>
            </div>

            <div class="field">
              <input type="text" name="streetAddress2">
              <label class="input-label" for="streetAddress2"><span>Street Address Line 2</span></label>
            </div>

            <b-row>
              <b-col cols="12" md="6">
                <div class="field">
                  <input type="text" name="city">
                  <label class="input-label" for="city"><span>City</span></label>
                </div>
              </b-col>

              <b-col cols="12" md="6">
                <div class="field">
                  <input type="text" name="region">
                  <label class="input-label" for="region"><span>Region</span></label>
                </div>
              </b-col>
            </b-row>

            <b-row>
              <b-col cols="12" md="5">
                <div class="field">
                  <input type="text" name="zip">
                  <label class="input-label" for="zip"><span>Zip</span></label>
                </div>
              </b-col>

              <b-col cols="12" md="7">
                <div class="field select-field is-filled">
                  <select-countries />
                  <label class="input-label" for="zip"><span>Country</span></label>
                </div>
              </b-col>
            </b-row>

            <div class="actions text-center">
              <button type="submit" class="btn btn-black btn-banner">
                Submit
              </button>
            </div>
          </form>

          <p class="detail-text mb-0">
            Some additional costs will be required as Xaurum transaction fees (0.5 XAUR per transaction) and as costs for securing international transport, that depend on quantity and your location (you can preview the options and costs <a href="https://en.posta.si/home" target="_blank">here</a> ). Be sure to check your country's gold taxation and other regulation.
          </p>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
import SidebarNavigation from '~/components/detail/sidebar-navigation.vue'
import SelectCountries from '~/components/forms/select-countries.vue'

export default {
  components: {
    SidebarNavigation,
    SelectCountries
  }
}
</script>
