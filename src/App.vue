<template>
  <div id="app" class="h-full">
    <Nav />
    <Account />
    <Tabs />
    <!-- <Timeline /> -->
  </div>
</template>

<script>
import Account from "./components/Account.vue";
import Nav from './components/Nav.vue';
import Tabs from './components/Tabs.vue';
// import Timeline from './components/Timeline.vue';

export default {
  name: "App",
  components: {
    Account,
    Nav,
    Tabs,
    // Timeline
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin-top: 60px;
}
</style>