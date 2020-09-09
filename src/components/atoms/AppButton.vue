<template>
  <button class="retardado" @click="say(title)">
    {{ title }}
  </button>
</template>

<script>
export default {
  name: 'AppButton',
  methods: {
    say() {
    },
  },
  props: ['title'],
};
</script>

<style lang="scss" scoped>
  .retardado{
    background: #11c76f;
    border-radius: 40px;
    color: #fff;
    width: 100%;
    display: inline-block;
    line-height: 40px;
    padding: 2px 16px;
    font-weight: bold;
    text-decoration: none;
    transition: 0.25s ease-in;
    text-align: center;
    max-width: 150px;
    font-size: 14px;
    border: 0px;
  }
</style>
