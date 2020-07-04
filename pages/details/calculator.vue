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
            FIAT to XAUR calculator
          </h1>

          <form id="formCalculator" novalidate="novalidate" autocomplete="off">
            <div layout="column" class="d-flex flex-column flex-md-row justify-content-center calculator-field-group">
              <div class="field number">
                <input
                  type="number"
                  name="amount"
                  min="0"
                >
                <label class="input-label" for="amount"><span>Amount</span></label>
              </div>

              <div class="field is-filled">
                <select name="currency">
                  <option value="EUR">
                    EUR
                  </option>
                  <option value="USD">
                    USD
                  </option>
                  <option value="AUD">
                    AUD
                  </option>
                  <option value="CZK">
                    CZK
                  </option>
                  <option value="BRL">
                    BRL
                  </option>
                  <option value="HRK">
                    HRK
                  </option>
                  <option value="RSD">
                    RSD
                  </option>
                </select>
                <label class="input-label" for="currency"><span>Currency</span></label>
              </div>
            </div>
          </form>

          <div class="text-center">
            <a href="#" class="btn btn-primary btn-big" disabled>Calculate</a>
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
