<template>

  <section class="cd-intro">
    <h1>Products Comparison Table</h1>
  </section> <!-- .cd-intro -->

  <section class="cd-products-comparison-table">
    <header>
      <h2>Compare Models</h2>

      <div class="actions">
        <a href="#0" class="reset">Reset</a>
        <a href="#0" class="filter">Filter</a>
      </div>
    </header>

    <div class="cd-products-table">
      <div class="features">
        <div class="top-info">Models</div>
        <ul class="cd-features-list">
          <li>Price</li>
          <li>Customer Rating</li>
          <li>Resolution</li>
          <li>Screen Type</li>
          <li>Display Size</li>
          <li>Refresh Rate</li>
          <li>Model Year</li>
          <li>Tuner Technology</li>
          <li>Ethernet Input</li>
          <li>USB Input</li>
          <li>Scart Input</li>
        </ul>
      </div> <!-- .features -->

      <div class="cd-products-wrapper">
        <ul class="cd-products-columns">
        <Product></Product>
        </ul> <!-- .cd-products-columns -->
      </div> <!-- .cd-products-wrapper -->

      <ul class="cd-table-navigation">
        <li><a href="#0" class="prev inactive">Prev</a></li>
        <li><a href="#0" class="next">Next</a></li>
      </ul>
    </div> <!-- .cd-products-table -->
  </section> <!-- .cd-products-comparison-table -->
</template>

<script>

import Product from "@/components/Product";

export default {
  name: 'Comparison',
  components: {
    Product
  },
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>

</style>
