<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Essential Links</h2>
    <Nav/>
  </div>
</template>

<script>
import Nav from "./Nav";

export default {
  name: "Home",
  data() {
    return {
      msg: "Welcome Home"
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
