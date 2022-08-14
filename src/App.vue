<script setup lang="ts">
import PageFooter from './components/PageFooter.vue';
</script>

<template>
  <n-config-provider>
    <n-global-style />
    <n-loading-bar-provider>
      <n-notification-provider>
        <router-view />
        <page-footer />
      </n-notification-provider>
    </n-loading-bar-provider>
  </n-config-provider>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Nunito&family=Roboto&display=swap');

* {
  font-family: 'Nunito', 'Roboto', Arial, Helvetica, sans-serif;
}
</style>
