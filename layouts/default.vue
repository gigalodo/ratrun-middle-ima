<template>
 <div>
   <AppHeader />
   <NuxtPage />
   <p>フッター！</p>
 </div>
</template>


<script>
import{AppHeader}from"../components/Organisms/Header";

export default {
  components:{AppHeader}
};
</script>


<style lang='scss' scoped>
</style>