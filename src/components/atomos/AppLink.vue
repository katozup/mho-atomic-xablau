<template>
  <a class="link" href="/about">
    {{ title }}
  </a>
</template>

<script>
export default {
  props: [
    'title',
  ],
};
</script>

<style lang="scss" scoped>
  .link {
    color: #11c76f;
    font-size: 15px;
    margin-right: 24px;
    text-decoration: none;
    transition: all 0.25s ease-in-out;
  }
</style>
