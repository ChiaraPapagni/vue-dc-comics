<template>
  <footer id="site_footer">
    <div class="footer_top">
      <div class="row container">
        <div>
          <h3>DC Comics</h3>
          <ul>
            <li><a href="">Characters</a></li>
            <li><a href="">Comics</a></li>
            <li><a href="">Movies</a></li>
            <li><a href="">TV</a></li>
            <li><a href="">Games</a></li>
            <li><a href="">Video</a></li>
            <li><a href="">News</a></li>
          </ul>
          <h3>Shop</h3>
          <ul>
            <li><a href="">Shop DC</a></li>
            <li><a href="">Shop DC Collectibles</a></li>
          </ul>
        </div>

        <div>
          <h3>DC</h3>
          <ul>
            <li><a href="">Terms Of Use</a></li>
            <li><a href="">Privacy policy (New)</a></li>
            <li><a href="">Ad Choices</a></li>
            <li><a href="">Advertising</a></li>
            <li><a href="">Jobs</a></li>
            <li><a href="">Subscriptions</a></li>
            <li><a href="">Talent Workshops</a></li>
            <li><a href="">CPSC Certificates</a></li>
            <li><a href="">Rating</a></li>
            <li><a href="">Shop Help</a></li>
            <li><a href="">Contact Us</a></li>
          </ul>
        </div>

        <div>
          <h3>Sites</h3>
          <ul>
            <li><a href="">DC</a></li>
            <li><a href="">MAD Magazine</a></li>
            <li><a href="">DC Kids</a></li>
            <li><a href="">DC Universe</a></li>
            <li><a href="">DC Power Visa</a></li>
          </ul>
        </div>
      </div>
    </div>
    <!-- /.footer_top -->

    <div class="footer_bottom">
      <div class="container">
        <div class="sign_up">
          <a href="">Sign-up now!</a>
        </div>
        <div class="social">
          <h3>Follow us</h3>
          <img src="../assets/img/footer-facebook.png" alt="facebook" />
          <img src="../assets/img/footer-twitter.png" alt="twitter" />
          <img src="../assets/img/footer-youtube.png" alt="youtube" />
          <img src="../assets/img/footer-pinterest.png" alt="pinterest" />
          <img src="../assets/img/footer-periscope.png" alt="periscope" />
        </div>
      </div>
    </div>
    <!-- /.footer_bottom -->
  </footer>
  <!-- /#site_footer -->
</template>

<script>
export default {};
</script>

<style lang="scss">
@import "../assets/scss/variables.scss";

.footer_top {
  background-image: url(../assets/img/footer-bg.jpg);

  .row {
    background-image: url(../assets/img/dc-logo-bg.png);
    background-repeat: no-repeat;
    background-position-y: center;
    background-position-x: right;
    padding: 2rem 0 3rem 0;

    & > div {
      padding-right: 2rem;
      h3 {
        color: #fff;
        font-size: 1.1rem;
        text-transform: uppercase;
        margin: 1rem 0;
      }

      ul {
        list-style: none;

        li a {
          color: grey;
          font-size: 0.85rem;
          text-decoration: none;
        }
      }
    }
  }
}

.footer_bottom {
  background-color: $dc_dark_gray_color;
  padding: 3rem 0;

  .container {
    display: flex;
    justify-content: space-between;
    align-items: center;

    .sign_up {
      a {
        color: #fff;
        text-decoration: none;
        text-transform: uppercase;
        padding: 0.8rem;
        border: 2px solid $dc_primary_color;
      }
    }

    .social {
      display: flex;
      align-items: center;

      h3 {
        color: $dc_primary_color;
        text-transform: uppercase;
      }

      img {
        margin-left: 1rem;
      }
    }
  }
}
</style>