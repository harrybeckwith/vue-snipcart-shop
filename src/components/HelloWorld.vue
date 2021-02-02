<template>
  <div class="hello">
    <button
      class="snipcart-add-item"
      data-item-id="starry-night"
      data-item-price="79.99"
      data-item-url="/"
      data-item-description="High-quality replica of The Starry Night by the Dutch post-impressionist painter Vincent van Gogh."
      data-item-image="/assets/images/starry-night.jpg"
      data-item-name="The Starry Night"
    >
      Add to cart
    </button>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
