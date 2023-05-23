<!-- 
<template>
 <Header>
<p>Headerのコンポーネントです。！；；</p>
 </Header>
</template>
-->

<template>
  <header>
    <nav>
      <li v-for="(link, key) in linkList" :key="key">
        <nuxt-link :to="link.to">{{ link.text }}</nuxt-link>
      </li>
    </nav>
  </header>
</template>

<script>
export default {
  setup() {
    const linkList = reactive([
      { text: "ホーム", to: "#" },
      { text: "経営理念", to: "#" },
      { text: "事業理念", to: "#" },
      { text: "事業目的", to: "#" },
      { text: "問い合わせ", to: "#" },
    ]);
    return { linkList };
  },
};
</script>

<style scoped>
nav {
  display: flex;
  gap: 20px;
}
li {
  list-style: none;
}
a {
  text-decoration: none;
}
</style>


