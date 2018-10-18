<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>All you need to know about us</h2>
    <Nav/>
  </div>
</template>

<script>
import Nav from "./Nav";

export default {
  name: "About",
  data() {
    return {
      msg: "About Us"
    };
  },
  components: {
    Nav
  }
};
</script>

<style scoped>
@import "../assets/css/app.css";
</style>
