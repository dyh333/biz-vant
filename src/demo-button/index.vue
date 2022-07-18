<template>
  <button class="demo-button">11<slot /></button>
</template>

<script>
export default {
  name: 'demo-button',

  props: {
    color: String,
    type: {
      type: String,
      default: 'primary',
    },
  },
};
</script>

<style lang="scss">
.demo-button {
  min-width: 120px;
  color: #fff;
  font-size: 16px;
  line-height: 36px;
  background-color: #f44;
  border: 1px solid #f44;
  border-radius: 30px;
}
</style>
