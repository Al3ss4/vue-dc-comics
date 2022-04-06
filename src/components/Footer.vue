<template>
  <footer>
    <div class="merchandise">
      <ul>
        <li>
          <img class="img-digital-comics"
            src="../assets/img/buy-comics-digital-comics.png"
            alt="digital-comics"
          /><a href="#" >DIGITAL COMICS</a>
        </li>
        <li>
          <img
            src="../assets/img/buy-comics-merchandise.png"
            alt="merchandise"
          /><a href="#">DC MERCHANDISE</a>
        </li>
        <li>
          <img
            src="../assets/img/buy-comics-subscriptions.png"
            alt="subscription"
          /><a href="#">SUBSCRIPTION</a>
        </li>
        <li>
          <img class="img-shop"
            src="../assets/img/buy-comics-shop-locator.png"
            alt="shop-locator"
          /><a href="#">COMIC SHOP LOCATOR</a>
        </li>
        <li>
          <img
            src="../assets/img/buy-dc-power-visa.svg"
            alt="digital-comics"
          /><a href="#">DC POWER VISA</a>
        </li>
      </ul>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterComponent",
};
</script>

<style lang="scss">
$bg-main: #ffffff;
$color-nav-bar: #67626a;
$color-border-btm: #0282f9;

.merchandise {
  background-color: $color-border-btm;

  ul {
    display: flex;
    justify-content: space-between;
    padding: 50px 200px;

    li {
      text-decoration: none;
      list-style: none;
      display: flex;
      align-items: center;
      img {
        width: 80px;
        padding: 0 10px;
        
      }
      .img-shop{
          width: 60px;
        }
        .img-digital-comics{
          width: 70px;
        }
      a {
        color: $bg-main;
        text-decoration-line: none;
        
      }
    }
  }
}
</style>