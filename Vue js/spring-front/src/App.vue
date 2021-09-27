
<template>
  <div id="app">
    <nav>
      <HomeLink />
      <NavLink url="/spring" text="Le programme Spring" />
      <NavLink url="/blog" text="Le blog" />
      <NavLink url="/collecte" text="Organiser une collecte" />
    </nav>
  </div>
</template>

<script>
import NavLink from "./components/NavLink.vue";
import HomeLink from "./components/HomeLink.vue";

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
  text-align: center;
  margin-top: 0;
}
</style>
