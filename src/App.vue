<template>
  <div>
    <Header></Header>

    <Footer></Footer>
  </div>
</template>

<script>
import Header from "./components/header/index.vue";
import Footer from "./components/footer/index.vue";

export default {
  name: "App",
  components: {
    Header, //不可使用header
    Footer,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
