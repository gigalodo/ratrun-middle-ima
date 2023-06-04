
<template>
  <footer>
    <div class="main">
      <div class="first">
        <img
          src="../../../assets/logo-2.png"
          alt="ラットランロゴ"
          class="ratlogo"
        />
        <p>
          Interior design <br />
          &<br />
          Construction
        </p>
      </div>
      <nav>
        <li v-for="(link, key) in linkList" :key="key">
          <nuxt-link :to="link.to">{{ link.text }}</nuxt-link>
        </li>
      </nav>
      <div class="third">
        <p>
          建築・建築デザイン・原状回復・内装解体・建物解体・アスベスト除去工事はSENTIAにお任せください！
        </p>
        <p>株式会社SENTIA</p>
        <p>〒454-0982</p>
        <p>愛知県名古屋市高見1-20-2</p>
        <p>TEL:052-1212-2029</p>
      </div>
    </div>
    <div class="sub">
      <small>(c) 店舗設計・デザイン・施工 CYPER.AllRight Reserved</small>
    </div>
  </footer>
</template>

<script>
export default {
  setup() {
    const linkList = reactive([
      { text: "ホーム", to: "#" },
      { text: "私たちについて", to: "#" },
      { text: "選ばれる理由", to: "#" },
      { text: "ワークフロー", to: "#" },
      { text: "FAQ", to: "#" },
      { text: "事例紹介", to: "#" },
    ]);
    const linkFooter = reactive([
      { text: "会社概要", to: "#" },
      { text: "お問合せ・お見積", to: "#" },
      { text: "個人情報保護法について", to: "#" },
    ]);

    return { linkList, linkFooter };
  },
};
</script>

<style scoped>
.sub {
  text-align: center;
}
small {
  /*うまく中央揃えにならない 
  text-align: center;*/
}
.ratlogo {
  width: 150px;
  height: auto; /* */
}

footer {
  /*height: 2000px;*/
}

.main {
  display: flex;
  padding: 100px 50px 30px 50px;
  color: white;
  background-color: rgb(199, 190, 190);
}

nav {
  gap: 20px;
  width: 30%;
}
li {
  list-style: none;
  padding-bottom: 10px;
}
a {
  color: white;
  text-decoration: none;
}

.first {
  /*なくなると何故かロゴがでかくなる */
  padding-right: 50px;
  width: 30%;
}

.third {
  border: 7px double white;
  /*box-shadow: 0 0 0 2px white, 0 0 0 4px rgb(199, 190, 190), 0 0 0 6px white;*/
  /*align-items: center;*/
  width: 300px;
  display: flex;
  flex-direction: column;
  width: 40%;
}
</style>


