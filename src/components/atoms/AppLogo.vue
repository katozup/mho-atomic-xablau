<template>
  <a @click="asdf('logo')">
    <svg xmlns="http://www.w3.org/2000/svg" id="svg" viewBox="0 0 129 44">
    </svg>
  </a>
</template>

<script>
export default {
  name: 'AppLogo',
  methods: {
    asdf() {
    },
  },
};
</script>

<style lang="scss">
  #svg{
    fill: #21c25e;
    height: 40px;
    transition: all 0.25s ease-in-out;
  }
</style>
