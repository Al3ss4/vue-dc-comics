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
        <img src="../assets/img/dc-logo-bg.png" alt="logo DC" />
      </div>
    </div>
    <div class="footer-btm clearfix">
      <div class="container">
        <h3 class="uppercase">Sign-Up Now!</h3>
        <img
          class="float-right padding"
          src="../assets/img/footer-facebook.png"
          alt=""
        />
        <img
          class="float-right padding"
          src="../assets/img/footer-twitter.png"
          alt=""
        />
        <img
          class="float-right padding"
          src="../assets/img/footer-youtube.png"
          alt=""
        />
        <img
          class="float-right padding"
          src="../assets/img/footer-pinterest.png"
          alt=""
        />
        <img
          class="float-right padding"
          src="../assets/img/footer-periscope.png"
          alt=""
        />
        <h2 class="uppercase float-right">Follow Us</h2>
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
$color-footer-btm: #303030;

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

  height: 400px;
  position: relative;
  padding: 50px 200px;

  .link-merchandise {
    display: flex;

    h3 {
      color: white;
      margin: 10px 20px;
    }
  }
  ul {
    display: flex;
    flex-direction: column;
    margin: 0px 20px;

    li {
      text-decoration: none;
      list-style: none;

      a {
        color: #576064;
        text-decoration-line: none;
      }
    }
  }

      img {
    width: 500px;
    padding: 0 20px;
    position: absolute;
    top: -60px;
    right: 80px;
  }
  

}
.footer-btm {
  background-color: $color-footer-btm;
  z-index: 900;
  padding: 25px 190px;
  height: 90px;
  .clearfix::after {
    content: "";
    clear: both;
    display: table;
  }
  h3 {
    color: white;
    padding: 10px 20px;
    border: 2px solid #0282f9;
    width: 11%;
    display: inline-block;
  }
  h2 {
    color: #0282f9;
    margin-right: 10px;
    line-height: 45px;
  }
}
.float-right {
  float: right;
}
.float-left {
  float: left;
}
.padding {
  padding: 5px;
}
</style>