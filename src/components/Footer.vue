<template>
  <footer>
    <div class="footer-top">
      <ul>
        <li>
          <img
            class="img-digital-comics"
            src="../assets/img/buy-comics-digital-comics.png"
            alt="digital-comics"
          /><a href="#">DIGITAL COMICS</a>
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
          <img
            class="img-shop"
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
    <div class="footer-middle">
      <div class="link-merchandise">
        <div class="col-1">
          <h3>DC COMICS</h3>
          <ul>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>
          <h3>SHOP</h3>
          <ul>
            <li><a href="#">Shop DC</a></li>
            <li><a href="#">Shop DC Collectibles</a></li>
          </ul>
        </div>
        <div class="col-2">
          <h3>DC</h3>
          <ul>
            <li><a href="#">Terms of Use</a></li>
            <li><a href="#">Privacy policy (New)</a></li>
            <li><a href="#">Ad Choise</a></li>
            <li><a href="#">Adverstising</a></li>
            <li><a href="#">Jobs</a></li>
            <li><a href="#">subscriptions</a></li>
            <li><a href="#">Talent Workshops</a></li>
            <li><a href="#">CPSC Certificates</a></li>
            <li><a href="#">Ratings</a></li>
            <li><a href="#">Shop Help</a></li>
            <li><a href="#">Contact Us</a></li>
          </ul>
        </div>
        <div class="col-3">
          <h3>SITES</h3>
          <ul>
            <li><a href="#">DC</a></li>
            <li><a href="#">MAD Magazine</a></li>
            <li><a href="#">DC Kids</a></li>
            <li><a href="#">DC Universe</a></li>
            <li><a href="#">DC Power Visa</a></li>
          </ul>
        </div>
      </div>
      <div class="logo-footer">
        <img src="../assets/img/dc-logo-bg.png" alt="logo DC">
      </div>
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

.footer-top {
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
      .img-shop {
        width: 60px;
      }
      .img-digital-comics {
        width: 70px;
      }
      a {
        color: $bg-main;
        text-decoration-line: none;
      }
    }
  }
}

.footer-middle {
  background-image: url(../assets/img/footer-bg.jpg);
  background-repeat: no-repeat;
  background-size: cover;
}
</style>