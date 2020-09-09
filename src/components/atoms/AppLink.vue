<template>
  <a class="a-link">
    {{ title }}
  </a>
</template>

<script>
export default {
  name: 'AppLink',
  props: [
    'title',
  ],
};
</script>
