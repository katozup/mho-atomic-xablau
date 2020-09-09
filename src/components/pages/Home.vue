<template>
  <div class="home">
    <AppLogo />
    <AppLink title="Sobre Nós" />
    <AppLink title="Duvidas Frequentes" />
    <AppLink title="Google" />
  </div>
</template>

<script>
import AppLogo from '../atomos/AppLogo.vue';
import AppLink from '../atomos/AppLink.vue';

export default {
  name: 'Home',
  components: {
    AppLogo,
    AppLink,
  },
};
</script>
