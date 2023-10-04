<script >
import { store } from '../src/store.js';
import appHeader from '../src/components/appHeader.vue';
import appJumbotron from './components/appJumbotron.vue';
import appTopMain from '../src/components/appTopMain.vue';
import appBottomMain from './components/appBottomMain.vue';
import appTopFooter from '../src/components/appTopFooter.vue';
import appBottomFooter from '../src/components/appBottomFooter.vue';

export default {
  name: "App",
  components: {
    appHeader,
    appJumbotron,
    appTopMain,
    appBottomMain,
    appTopFooter,
    appBottomFooter,


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
  <appTopFooter></appTopFooter>
  <appBottomFooter></appBottomFooter>
</template>

<style lang="scss" scoped>
h1 {
  background-color: red;
}
</style>