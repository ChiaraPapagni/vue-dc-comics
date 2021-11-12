<template>
  <div class="comics_card">
    <img :src="image" alt="title" />
    <p>{{ title }}</p>
  </div>
  <!-- /.comics_card -->
</template>

<script>
export default {
  props: {
    image: String,
    title: String,
  },
};
</script>

<style lang="scss">
.comics_card {
  img {
    width: 200px;
    height: 200px;
    object-fit: cover;
    object-position: top;
  }

  p {
    width: 200px;
    font-size: 0.9rem;
    text-transform: uppercase;
    padding: 1rem 0 2.5rem 0;
  }
}
</style>