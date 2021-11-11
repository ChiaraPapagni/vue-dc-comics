<template>
  <header id="site_header">
    <nav class="navbar container">
      <img src="../assets/img/dc-logo.png" alt="DC Comics" />

      <ul>
        <li><a href="">Characters</a></li>
        <li><a href="" class="active">Comics</a></li>
        <li><a href="">Movies</a></li>
        <li><a href="">Tv</a></li>
        <li><a href="">Games</a></li>
        <li><a href="">Collectibles</a></li>
        <li><a href="">Video</a></li>
        <li><a href="">Fans</a></li>
        <li><a href="">News</a></li>
        <li><a href="">Shop</a></li>
      </ul>
    </nav>
    <!-- /.navbar -->
  </header>
  <!-- /#site_header -->
</template>

<script>
export default {};
</script>

<style lang="scss">
@import "../assets/scss/variables.scss";

#site_header {
  padding: 1rem;

  .navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  img {
    width: 80px;
    height: 80px;
  }

  ul {
    display: flex;
    list-style: none;

    a {
      color: $dc_dark_text_color;
      font-size: 0.85rem;
      font-weight: bold;
      text-decoration: none;
      text-transform: uppercase;
      margin: 0 1rem;
      padding: 2rem 0;

      &.active {
        color: $dc_primary_color;
        border-bottom: 4px solid $dc_primary_color;
      }
    }
  }
}
</style>