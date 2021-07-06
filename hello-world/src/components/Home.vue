<template>
  <div class="home">
    <h1>Hello From Home component</h1>
    <Users />
    <Products />
  </div>
</template>
<script>
import Users from "./Users.vue";
import Products from "./Products.vue";

export default {
  name: "Home",
  components: {
    // HelloWorld,
    Users,
    Products,
  },
};
</script>
<style scoped>
.home {
  background-color: aquamarine;
  height: 500px;
}
</style>>
