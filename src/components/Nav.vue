<template>
  <ul>
    <li>
      <a href="/">
            Home
        </a>
    </li>
    <li>
      <a href="/about" target="_blank">
        <router-link to="/about">
          About
        </router-link>
      </a>
    </li>
    <li>
      <a href="#" target="_blank">
        <router-link to="/terms">
          Terms
        </router-link>
      </a>
    </li>
  </ul>
</template>

<script>
export default {
  name: "Nav"
};
</script>

<style scoped>
@import "../assets/css/app.css";
</style>
