
<template>
  <div>
    <div class="back-pic">
      <div class="main-first">
        <h1>理念の文章が入ります</h1>
        <p>
          母体が内装解体専門会社であるからこそ、一般的な施工会社よりも解体費用を抑えることができます。つまり、解体費用を抑えることで、余力のある資金が生まれ、使い道を広げることができるということです。
          <br />選択のできる予算の使途も合わせてご提案いたします。
        </p>
      </div>
    </div>
    <div class="container">
      <h3>メインタイトルが</h3>
      <p class="description">
        タイトルが入ります。タイトルが入ります。タイトルが入ります。タイトルが入ります。タイトルが入ります。タイトルが入ります。タイトルが入ります。タイトルが入ります。タイトルが入ります。タイトルが入ります。タイトルが入ります。タイトルが入ります。
        タイトルが入ります。タイトルが入ります。タイトルが入ります。タイトルが入ります。タイトルが入ります。タイトルが入ります。タイトルが入ります。タイトルが入ります。
      </p>
      <h3>経営理念 PHILOSOPHY</h3>
      <div class="flex-box">
        <img class="two" src="../assets/長方形 9.png" alt="" />
        <div class="two flex-description">
          <h4>テキストが入ります。テキストが入ります。テキストが入ります。</h4>
          <p>
            テキストが入ります。テキストが入ります。テキストが入ります。テキストが入ります。テキストが入ります。
          </p>
        </div>
      </div>
      <div class="flex-box">
        <div class="two flex-description">
          <h4>テキストが入ります。テキストが入ります。テキストが入ります。</h4>
          <p>
            テキストが入ります。テキストが入ります。テキストが入ります。テキストが入ります。テキストが入ります。
          </p>
        </div>
        <img class="two" src="../assets/長方形 9.png" alt="" />
      </div>

      <h3>事業目的 VISION</h3>
      <h3>事業使命 MISSION</h3>
      <h3>情報技術とデザインと思想</h3>
      <h3>デザインの概要</h3>
      <h3>デザイン受賞歴</h3>
    </div>
  </div>
</template>


<script>
export default {};
</script>
<style lang="scss" scoped>
body {
}

.back-pic {
  color: aliceblue;
  height: 700px;
  background: url(../assets/cyber-g15cd33eba_1920.png);
  background-size: cover;
  position: relative;
}
.main-first {
  /*float: right;
  text-align: right;*/
  /*padding: 10px 10px 10px 900px;*/
  position: absolute;
  right: 0px;
  top: 20%;
  padding-right: 30px;
  font-size: 24px;
  width: 600px;
}
.main-first h1 {
  font-size: 60px;
}

.container {
  padding: 20px 40px;
}

h3 {
  text-align: center;
  font-size: 48px;
}

.description {
  padding: 20px 200px;
}

.flex-box {
  display: flex;
}

.two {
  width: 50%;

  margin: 0px 20px;
}

.flex-description {
  padding: 0px 40px;
}

h4 {
  font-size: 30px;
}
</style>