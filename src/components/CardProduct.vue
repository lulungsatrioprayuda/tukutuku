<template>
  <div class="card shadow card-product">
    <img
      class="card-img-top"
      :src="require(`../assets/images/${product.gambar}`)"
      alt="..."
    />
    <div class="card-body">
      <h5 class="card-title">{{ product.nama }}</h5>
      <hr>
      <p class="card-text">Harga : Rp.{{ product.harga }}</p>
      <router-link class="btn btn-success" :to="'/foods/'+product.id">
        <b-icon-cart></b-icon-cart> Pesan
      </router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: "CardProduct",
  props: ["product"],
};
</script>

<style>
</style>