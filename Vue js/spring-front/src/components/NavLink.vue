<script>
export default {
  name: "NavLink",
  props: ["url", "text"],
};
</script>

<template>
  <a href="url">{{ text }}</a>
</template>

<style>
a {
  text-decoration: none;
  color: #ffffff;
  font-weight: 900;
  font-size: 18px;
  font-family: Raleway;
}
</style>