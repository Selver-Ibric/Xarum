<template>
  <div class="graphs-section">
    <b-container>
      <b-row class="text-center text-lg-left graphs-row">
        <b-col cols="12" lg="5">
          <b-row>
            <b-col cols="4" class="pr-0">
              <button class="w-100 btn btn-secondary" :class="[showGraph1 ? 'btn-primary' : '']" @click="showGraphOne">
                {{ $t('graphs.graph1BtnText') }}
              </button>
            </b-col>

            <b-col cols="4" class="px-0">
              <button class="w-100 btn btn-secondary" :class="[showGraph2 ? 'btn-primary' : '']" @click="showGraphTwo">
                {{ $t('graphs.graph2BtnText') }}
              </button>
            </b-col>

            <b-col cols="4" class="pl-0">
              <button class="w-100 btn btn-secondary" :class="[showGraph3 ? 'btn-primary' : '']" @click="showGraphThree">
                {{ $t('graphs.graph3BtnText') }}
              </button>
            </b-col>
          </b-row>

          <div class="graph-content">
            <h1 class="graph-title">
              {{ $t('graphs.graphTitle') }}
            </h1>

            <p class="graph-text">
              {{ $t('graphs.graphText') }}
            </p>
          </div>
        </b-col>

        <b-col cols="12" lg="7" class="px-0">
          <div v-if="showGraph1" class="graph-image-container">
            <graph-1 />
          </div>

          <div v-if="showGraph2" class="graph-image-container">
            <graph-2 />
          </div>

          <div v-if="showGraph3" class="graph-image-container">
            <graph-3 />
          </div>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
import Graph1 from '~/components/graph/graph-1.vue'
import Graph2 from '~/components/graph/graph-2.vue'
import Graph3 from '~/components/graph/graph-3.vue'

export default {
  components: {
    Graph1,
    Graph2,
    Graph3
  },
  data () {
    return {
      showGraph1: true,
      showGraph2: false,
      showGraph3: false
    }
  },
  methods: {
    showGraphOne () {
      this.showGraph1 = true
      this.showGraph2 = false
      this.showGraph3 = false
    },
    showGraphTwo () {
      this.showGraph1 = false
      this.showGraph2 = true
      this.showGraph3 = false
    },
    showGraphThree () {
      this.showGraph1 = false
      this.showGraph2 = false
      this.showGraph3 = true
    }
  }
}
</script>
