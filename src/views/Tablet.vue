<template>

  <div class="tablet">
    <div class="header">
      <h1>VETERAN NM 2024</h1>
    </div>
    <div class="ril"></div>
    <div class="lia"></div>

    <div class="content"></div>
  </div>

</template>

<script>
export default {
  name: "Tablet"
}
</script>

<style lang="scss">
  .tablet {
    .header {
      height: 100px;
      background-image: url("src/assets/tablet-header.png");
      background-position: center center;
      background-repeat: no-repeat;
      width: 100%;

      h1 {
        color: white;
        font-size: 50px;
        text-align: center;
        padding-top: 25px;
        -webkit-text-stroke-width: 2px;
        -webkit-text-stroke-color: black;
      }
    }

    .ril {
      height: 100px;
      background-image: url("src/assets/ril-tablet.png");
      position: absolute;
      width: 170px;
      left: 0;
      top: 0;
    }

    .lia {
      height: 100px;
      background-image: url("src/assets/lia-tablet.png");
      position: absolute;
      width: 170px;
      right: 0;
      top: 0;
    }

    .content {
           position: relative;
           height: 100%;
           max-width: 90%;
           margin: auto;
           background-color: #192a66;
           padding-top: 50px;
    }
  }
</style>
