<template>
  <header>
    <div>
      <img src="../assets/img/dc-logo.png" alt="logo" />
    </div>
    <div class="nav-bar">
      <ul>
        <li><a href="#">CHARACTERS</a></li>
        <li><a href="#">COMICS</a></li>
        <li><a href="#">MOVIES</a></li>
        <li><a href="#">TV</a></li>
        <li><a href="#">GAMES</a></li>
        <li><a href="#">COLLECTIBLES</a></li>
        <li><a href="#">VIDEOS</a></li>
        <li><a href="#">FANS</a></li>
        <li><a href="#">NEWS</a></li>
        <li><a href="#">SHOP</a></li>
      </ul>
    </div>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
};
</script>

<style lang="scss" scoped >
$bg-main: #ffffff;
$color-nav-bar: #67626a;

header {
  background-color: $bg-main;
  display: flex;
  justify-content: space-around;
}

.nav-bar {
  display: flex;

  ul {
   
    li {
      text-decoration: none;
      list-style: none;
      a {
        color: #67626a;
        text-decoration-line: none;
      }
      a:hover {
        color: blue;
      }
    }
  }
}
</style>