<style>
.container {
  width: 800px;
  margin: auto;
  padding: 1rem;
}
.detail {
  display: grid;
  grid-template-columns: 30% 70%;
  grid-column-gap: 1rem;
}
.detail img {
  width: 100%;
}
.carousel {
  width: 800px;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-column-gap: 1rem;
}
.carousel img {
  width: 100%;
}
</style>

<template>
<div class="container">
  <Header />
  <div class="detail">
    <img src="https://placedog.net/500/280?id=40" />
    <div>
      <h1>Cindy</h1>
      <p>Cindy is a fabulous dog with a great personality...</p>
    </div>
  </div>
  <hr />
  <h1>More Adoptable Dogs</h1>
  <div class="carousel">
    <div>
      <img src="https://placedog.net/500/280?id=60" alt="Dog 60">
      <h1>Cutie</h1>
    </div>
    <div>
      <img src="https://placedog.net/500/280?id=61" alt="Dog 61">
      <h1>Ace</h1>
    </div>
    <div>
      <img src="https://placedog.net/500/280?id=62" alt="Dog 62">
      <h1>Spot</h1>
    </div>
  </div>
</div>
</template>

<script>
  import Header from 'home/Header';

  export default {
    components: {
      Header,
    }
  }
</script>