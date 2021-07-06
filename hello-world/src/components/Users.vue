<template>
  <div class="child">
    <input type="text" name="" id="" v-model="massage" />
    <h1 style="white-space: pre-line">{{ massage }}</h1>
  </div>
</template>
<script>
export default {
  name: "Users",
  data() {
    return {
      massage: "Users component",
    };
  },
};
</script>
<style scoped>
.child {
  background-color: rgb(240, 133, 46);
  height: 100px;
  width: 200px;
  padding: 60px;
  margin: 20px;
}
</style>>
