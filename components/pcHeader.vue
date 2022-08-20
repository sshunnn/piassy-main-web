<template>
  <header>
    <h1>
      <a href="/">華麗なる居酒屋</a>
    </h1>
    <nav class="pc-nav">
      <ul>
        <li><a href="Profile">ABOUT</a></li>
        <li><a href="detail">SERVICE</a></li>
        <li><a href="contact">COMPANY</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {};
</script>

<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  padding: 0;
  font-family: "Hiragino Kaku Gothic Pro", "ヒラギノ角ゴ Pro W3", メイリオ,
    Meiryo, "ＭＳ Ｐゴシック", "Helvetica Neue", Helvetica, Arial, sans-serif;
  background-color: #e6e6e6;
}
header {
  padding: 30px 4% 10px;
  position: fixed;
  top: 0;
  width: 100%;
  background-color: #fff;
  display: flex;
  align-items: center;
}
h1 {
  margin: 0;
  padding: 0;
  font-size: 20px;
}
a {
  text-decoration: none;
  color: #4b4b4b;
}
ul {
  list-style: none;
  margin: 0;
}
ul {
  list-style: none;
  margin: 0;
  display: flex;
}
li {
  margin: 0 0 0 15px;
  font-size: 14px;
}
nav {
  margin: 0 0 0 auto;
}
</style>
