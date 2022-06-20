<template>
  <div id="app">
    <TitleOfThePage></TitleOfThePage>
    <JumboTron></JumboTron>
  </div>
</template>

<script>
import Title from "./components/TitleOfThePage.vue";
import Jumbo from "./components/JumboTron.vue";

export default {
  name: "App",
  components: {
    TitleOfThePage: Title,
    JumboTron: Jumbo,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
