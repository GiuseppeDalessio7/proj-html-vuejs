<script >
import { store } from '../src/store.js';
import appheader from '../src/components/appHeader.vue'
import appMain from '../src/components/appMain.vue'
import appFooter from '../src/components/appFooter.vue'


export default {
  name: "App",
  components: {
    appheader,
    appMain,
    appFooter,

  },
  data() {
    return {
      store,

    }
  },

}

</script>




<template>
  <h1>Ciao</h1>
  <appheader></appheader>
  <appMain></appMain>
  <appFooter></appFooter>
</template>

<style lang="scss" scoped>
h1 {
  background-color: red;
}
</style>