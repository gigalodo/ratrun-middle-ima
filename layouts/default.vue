<template>
  <div>
    <AppHeader />
    <NuxtPage />
    <AppFooter />
  </div>
</template>


<script>
import { AppFooter } from "../components/Organisms/Footer";
import { AppHeader } from "../components/Organisms/Header";

export default {
  components: { AppHeader, AppFooter },
};
</script>


<style lang='scss' scoped>
</style>