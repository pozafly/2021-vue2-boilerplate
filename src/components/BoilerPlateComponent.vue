<template>
  <div class="start">{{ msg }}</div>
</template>

<script>
export default {
  props: {
    msg: {
      type: String,
      default: '',
    },
  },
};
</script>

<style lang="scss" scoped>
.start {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  font-size: 30px;
}
</style>
