<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <Nav/>
  </div>
</template>

<script>
import Nav from "./Nav";

export default {
  name: "Terms",
  data() {
    return {
      msg: "Terms & Conditions"
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
