<template>
  <header>
    <div class="logo">
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
$color-border-btm: #0282f9;

header {
  background-color: $bg-main;
  display: flex;
  justify-content: space-around;
  min-height: 60px;
  padding: 10px 0;
  align-items: center;
}

.logo{
  img{
    width: 70px;
  }
}
.nav-bar {
  
  ul {
    display: flex;
    justify-content: space-between;
    
    
    li {
      text-decoration: none;
      list-style: none;
      padding:0 20px;

      a {
        color: #67626a;
        text-decoration-line: none;
        
      }
      a:hover {
        color: $color-border-btm;
        border-bottom: 2px solid $color-border-btm;
      }
    }
  }
}
</style>