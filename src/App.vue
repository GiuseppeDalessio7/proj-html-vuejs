<script >
import { store } from '../src/store.js';
import appHeader from '../src/components/appHeader.vue';
import appJumbotron from './components/appJumbotron.vue';
import appTopMain from '../src/components/appTopMain.vue';
import appBottomMain from './components/appBottomMain.vue';
import appFooter from '../src/components/appFooter.vue';


export default {
  name: "App",
  components: {
    appHeader,
    appTopMain,
    appBottomMain,
    appFooter,
    appJumbotron

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
  <appJumbotron></appJumbotron>
  <appTopMain></appTopMain>
  <appBottomMain></appBottomMain>
  <appFooter></appFooter>
</template>

<style lang="scss" scoped>
h1 {
  background-color: red;
}
</style>