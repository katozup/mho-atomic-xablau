<template>
  <div class="o-header">
    <div class="o-header-logo">
      <AppLogo />
    </div>
    <div class="o-header-linksmenu">
      <AppLink title="sobre nós" />
      <AppLink title="duvidas frequentes" />
      <AppLink title="central de doaçoes" />
      <AppLink title="gerador de QR code" />
      <AppButton title="erf" />
    </div>
  </div>
</template>

<script>
import AppLogo from '../atoms/AppLogo.vue';
import AppLink from '../atoms/AppLink.vue';
import AppButton from '../atoms/AppButton.vue';

export default {
  name: 'AppHeader',
  components: {
    AppLogo,
    AppLink,
    AppButton,
  },
};
</script>

<style lang="scss" scoped>
  .o-header{
    justify-content: flex-start;
    text-align: start;
    height: 100%;

    .o-header-logo {
      flex-basis: 16.66666667%;
      max-width: 16.66666667%;
      box-sizing: border-box;
      -webkit-box-flex: 0;
      -ms-flex: 0 0 auto;
      flex: 0 0 auto;
      padding-right: 0.5rem;
      padding-left: 0.5rem;
    }

    .o-header-linksmenu{
      display: flex;
      align-items: center;
      justify-content: flex-end;
      flex-basis: 83.33333333%;
      max-width: 83.33333333%;

      .a-link{
        color: #11c76f;
        text-decoration: none;
        transition: all 0.25s ease-in-out;
        margin-right: 4%;
        font-size: 16px;
      }
    }
  }
</style>
