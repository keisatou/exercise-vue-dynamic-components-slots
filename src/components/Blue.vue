<template>
  <div>
    <slot></slot>
  </div>
</template>

<script>
export default {
  activated() {
    console.log('Blue.vue Activated!');
  },
  deactivated() {
    console.log('Blue.vue Deactivated!');
  },
};
</script>

<style scoped>
div {
  border: 1px solid blue;
  background-color: lightblue;
  padding: 30px;
  margin: 20px auto;
  text-align: center
}
</style>
