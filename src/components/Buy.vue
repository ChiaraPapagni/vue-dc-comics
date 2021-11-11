<template>
  <div class="row_cards">
    <ul>
      <li>
        <img
          src="../assets/img/buy-comics-digital-comics.png"
          alt="Digital comics"
        />
        <p>Digital comics</p>
      </li>
      <li>
        <img
          src="../assets/img/buy-comics-merchandise.png"
          alt="DC merchandise"
        />
        <p>DC merchandaise</p>
      </li>
      <li>
        <img
          src="../assets/img/buy-comics-subscriptions.png"
          alt="Subscription"
        />
        <p>Subscription</p>
      </li>
      <li>
        <img
          src="../assets/img/buy-comics-shop-locator.png"
          alt="Comic shop locator"
        />
        <p>Comic shop locator</p>
      </li>
      <li>
        <img src="../assets/img/buy-dc-power-visa.svg" alt="DC power visa" />
        <p>DC power visa</p>
      </li>
    </ul>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
@import "../assets/scss/variables.scss";

.row_cards {
  width: 100%;
  background-color: $dc_primary_color;
  padding: 3rem 0;
  color: #fff;

  img {
    height: 50px;
  }

  li:last-child img {
    height: 40px;
  }

  ul {
    display: flex;
    justify-content: center;
    list-style: none;

    li {
      display: flex;
      align-items: center;
      padding: 0 2rem;

      p {
        font-size: 0.9rem;
        text-transform: uppercase;
        padding-left: 1rem;
      }
    }
  }
}
</style>