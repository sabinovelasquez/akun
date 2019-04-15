<template lang='pug'>
  v-layout.fullImg(align-center, justify-center, row, fill-height, white--text)
    v-container
      .text-xs-center
        v-img.centerImg(:src='require("../assets/logo-w.svg")', width='100')
        p.font-weight-light
          .subheading Chilean International Importer
        p
          v-btn.white--text(color='grey darken-4', large)
            | Contact
            v-icon(right) email

</template>

<script>
export default {
  name: 'Landing',
  data() {
    return {
    };
  },

  mounted() {
    // this.geolocate();
  }
};
</script>
<style lang='scss'>
.centerImg{
  margin: auto;
}
.fullImg{
  background-image: url("../assets/containers.jpg");
  background-size: cover;
  // -webkit-filter: blur(2px);
  // filter: blur(2px);
}
</style>