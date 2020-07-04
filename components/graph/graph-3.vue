<template>
  <div>
    <graph-area
      :height="500"
      :padding-top="0"
      :padding-bottom="0"
      :padding-right="20"
      :padding-left="35"
      :axis-max="2400"
      :axis-x-position="'top'"
      :axis-full-mode="true"
      :shape="'normal'"
      :opacity="1"
      :borderline="true"
      :labels="labels"
      :values="values"
    >
      <legends :names="names" align="left" />
      <guideline :tooltip-y="true" />
    </graph-area>
  </div>
</template>

<script>
export default {
  data () {
    return {
      names: ['Price'],
      labels: [2010, 2011, 2012, 2013, 2014, 2015, 2016, 2017, 2018, 2019, 2020],
      values: [
        [793, 981, 1052, 902, 768, 821, 926, 976, 950, 1093, 1224]
      ]
    }
  }
}
</script>
