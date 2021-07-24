<template>
  <div class="hero">
    <!-- Dekstop -->
    <div class="d-none d-md-block">
      <div class="row mt-4">
        <div class="col-md-6">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h2>
                <strong>Makanan yang lezat,</strong>
                <br />ada di Gadetmu!
              </h2>
              <p>Tunggu apalagi? ambil hp Anda, lalu pesan makanan lezatnya</p>
              <router-link class="btn btn-success" to="/Foods">
                <b-icon-arrow-right />&nbsp;Pesan
              </router-link>
            </div>
          </div>
        </div>
        <div class="col-md-6">
          <img src="../assets/images/hero.png" width="100%" />
        </div>
      </div>
    </div>

    <!-- /Dekstop -->

    <!-- Mobile -->
    <div class="d-sm-block d-md-none">
      <div class="row mt-4 mb-3">
        <div class="col-md-6">
          <img src="../assets/images/hero.png" width="100%" />
        </div>

        <div class="col-md-6 ">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h2>
                <strong>Makanan yang lezat,</strong>
                <br />ada di Gadetmu!
              </h2>
              <p>Tunggu apalagi? ambil hp Anda, lalu pesan makanan lezatnya</p>
              <button class="btn btn-success">
                <b-icon-arrow-right />&nbsp;Pesan
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- /Mobile -->
  </div>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<style></style>
