<template>
  <div></div>
</template>

<script>
export default {
  activated() {
    console.log('Green.vue Activated!');
  },
  deactivated() {
    console.log('Green.vue Deactivated!');
  },
};
</script>

<style scoped>
div {
  border: 1px solid green;
  background-color: lightgreen;
  padding: 30px;
  margin: 20px auto;
  text-align: center;
}
</style>
