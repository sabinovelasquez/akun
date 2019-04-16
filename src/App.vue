<template lang='pug'>
  v-app
    Landing
    Footer
</template>

<script>
import Landing from './components/Landing'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    Landing,
    Footer
  },
  data () {
    return {
      //
    }
  }
}
</script>
<style lang='scss'>
</style>
