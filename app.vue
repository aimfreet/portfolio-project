<template>
    <TheHeader />
    <NuxtPage />
</template>
 
<script>
import TheHeaderVue from './components/TheHeader.vue';

export default {
  components: {
    TheHeaderVue,
  }
}
</script>

<style lang="scss">
    @import './assets/style.scss';
</style>