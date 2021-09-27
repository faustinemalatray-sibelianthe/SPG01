
<template>
  <div id="app">
    <nav>
      <HomeLink />
      <NavLink url="/spring" text="Le programme Spring" />
      <NavLink url="/blog" text="Le blog" />
      <NavLink url="/collecte" text="Organiser uen collecte" />
    </nav>
  </div>
</template>

<script>
import NavLink from "./components/NavLink.vue";
import HomeLink from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    NavLink,
    HomeLink,
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
