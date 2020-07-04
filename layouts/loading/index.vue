<template>
  <div class="loading-container justify-content-center align-items-center" :class="{ 'd-none' : !isLoading}">
    <div class="loading-img-container">
      <svg
        version="1.1"
        xmlns="http://www.w3.org/2000/svg"
        xmlns:xlink="http://www.w3.org/1999/xlink"
        preserveAspectRatio="xMidYMid meet"
        viewBox="0 0 290 290"
        width="290"
        height="290"
        class="loading-img"
      ><defs><path id="b9Ar2a3Cq" d="M210.22 3L210.22 67.83L156.85 67.83L145.61 79.06L145.61 132.19L84.28 132.19L81 129.15L81 67.83L134.14 67.83L145.61 56.36L145.61 3L210.22 3Z" /><path id="d4b9oSdiEy" d="M3 78.4L67.61 78.4L67.61 131.53L79.08 143.24L132.22 143.24L132.22 204.32L128.94 207.6L67.61 207.6L67.61 154.47L56.14 143.24L3 143.24L3 78.4Z" /><path id="a2bSBvwPdP" d="M288.22 210.2L223.61 210.2L223.61 157.07L212.37 145.84L159 145.84L159 84.52L162.28 81L223.61 81L223.61 134.13L235.08 145.84L288.22 145.84L288.22 210.2Z" /><linearGradient
        id="gradienta26qqenrcQ"
        gradientUnits="userSpaceOnUse"
        x1="223.61"
        y1="81"
        x2="223.61"
        y2="288.6"
      ><stop style="stop-color: #f6ca63;stop-opacity: 1" offset="0%" /><stop style="stop-color: #a67c20;stop-opacity: 1" offset="100%" /></linearGradient><path id="a4th9H0aPY" d="M81 288.2L81 223.6L134.14 223.6L145.61 212.13L145.61 159L206.71 159L210.22 162.51L210.22 223.6L156.85 223.6L145.61 235.07L145.61 288.2L81 288.2Z" /><linearGradient
        id="gradientaGs5jFem"
        gradientUnits="userSpaceOnUse"
        x1="145.61"
        y1="288.19"
        x2="145.61"
        y2="80.59"
      ><stop style="stop-color: #a2791f;stop-opacity: 1" offset="0%" /><stop style="stop-color: #f6ca63;stop-opacity: 1" offset="100%" /></linearGradient></defs><g><g><g><g><use
        xlink:href="#b9Ar2a3Cq"
        opacity="1"
        fill-opacity="0"
        stroke="#e0b551"
        stroke-width="3"
        stroke-opacity="1"
      /></g></g><g><g><use
        xlink:href="#d4b9oSdiEy"
        opacity="1"
        fill-opacity="0"
        stroke="#e0b551"
        stroke-width="3"
        stroke-opacity="1"
      /></g></g><g><use xlink:href="#a2bSBvwPdP" opacity="1" fill="url(#gradienta26qqenrcQ)" /><g><use
        xlink:href="#a2bSBvwPdP"
        opacity="1"
        fill-opacity="0"
        stroke="#000000"
        stroke-width="1"
        stroke-opacity="0"
      /></g></g><g><use xlink:href="#a4th9H0aPY" opacity="1" fill="url(#gradientaGs5jFem)" /><g><use
        xlink:href="#a4th9H0aPY"
        opacity="1"
        fill-opacity="0"
        stroke="#000000"
        stroke-width="1"
        stroke-opacity="0"
      /></g></g></g></g></svg>
    </div>
  </div>
</template>

<script>

export default {
  data () {
    return {
      isLoading: true
    }
  },
  mounted () {
    setTimeout(() => {
      this.isLoading = false
    }, 3000)
  }
}
</script>

<style lang="css">
    .loading-container {
        position: fixed;
        display: flex;
        width: 100vw;
        height: 100vh;
        background: rgb(27, 31, 38);
        z-index: 9999;
        overflow: hidden;
        opacity: 1;
        transition: opacity .5s;
    }

    .not-active {
        opacity: 0;
    }

    .loading-img-container {
        position: relative;
        animation-name: jump;
        animation-iteration-count: infinite;
        animation-duration: 1.5s;
        animation-timing-function: linear;
    }

    .loading-img {
        max-width: 100%;
        width: 80px;
    }

    @keyframes jump {
        0% {
            top: -15px;
        }
        50% {
            top: 15px;
        }
        100% {
            top: -15px;
        }
    }
</style>
