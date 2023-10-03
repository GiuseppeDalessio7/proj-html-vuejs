<script >
import { store } from '../src/store.js';
import appHeader from '../src/components/appHeader.vue'
import appMain from '../src/components/appMain.vue'
import appFooter from '../src/components/appFooter.vue'


export default {
  name: "App",
  components: {
    appHeader,
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
  <appHeader></appHeader>
  <appMain></appMain>
  <appFooter></appFooter>
</template>

<style lang="scss" scoped>
h1 {
  background-color: red;
}
</style>