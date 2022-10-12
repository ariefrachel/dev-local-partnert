<template>
  <div class="conta">
    <NavigationApp />
    <div class="container-fluid">
      <div class="pesan-dk">
        <div class="row">
          <div class="col-lg-6 bg-primary"  style="padding: 100px 60px 0px">
            <div class="bungkuss">
                    <h2 class="terbaru">Cek Pemesanan</h2>
              <p>
                Cek kode pemesanan dibawah untuk melihat detail pemesanan paket
                wisata yang sudah kamu pesan.
              </p>
                  </div>
                  <div class="input-group mb-3" style="width:98%;">
                  <input
                  v-model="search"
                    type="text"
                    class="form-control"
                    placeholder="Cari partnert anda"
                    aria-label="Cari"
                    aria-describedby="button-addon2"
                    
                  />
                  <button
                    class="btn btn-outline-secondary"
                    type="button"
                    id="button-addon2"
                    @click="cariKode"
                  >
                    <b-icon-search></b-icon-search>
                    Cari
                  </button>
                
                </div>
            <div class="container">
              <div class="row">
                <div class="col-lg-10 bg-warning">
                 <div class="row">
                  <div class="col-md-4 bg-black">
                    <h3>hello</h3>
                  </div>
                  <div class="col-md-4 bg-black">
                    <h3>hello</h3>
                  </div>
                 </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-6">
            <div class="bungkuss">
              <img
                style="width: 100%"
                src="@/assets/img/testimoni/image 7.png"
                alt=""
              />
            </div>
          </div>
        </div>
      </div>

      <div class="pesan-mb">
        <div class="row">
          <div class="col-lg-6"></div>
          <div class="col-lg-6">
            <div class="bungkuss">
              <img
                style="width: 100%"
                src="@/assets/img/testimoni/image 7.png"
                alt=""
              />
            </div>
            <div class="container">
              <div class="row" style="padding: 10px 10px 0px">
                <div class="col-lg-5">
                  <div class="bungkuss">
                    <h2 class="terbaru">Cek Pemesanan</h2>
              <p>
                Cek kode pemesanan dibawah untuk melihat detail pemesanan paket
                wisata yang sudah kamu pesan.
              </p>
                  </div>
                  
                </div>
              </div>
              <div class="input-group mb-3">
                  <input
                  v-model="search"
                    type="text"
                    class="form-control"
                    placeholder="Cari partnert anda"
                    aria-label="Cari"
                    aria-describedby="button-addon2"
                    
                  />
                  <button
                    class="btn btn-outline-secondary"
                    type="button"
                    id="button-addon2"
                    @click="cariKode"
                  >
                    <b-icon-search></b-icon-search>
                    Cari
                  </button>
                
                </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import NavigationApp from "./NavigationApp.vue";
export default {
  components: { NavigationApp },
};
</script>
<style>
.pesan-mb {
  display: none;
}
@media only screen and (max-width: 768px) {
  .pesan-dk{
    display: none;
  }
  .pesan-mb{
    display: block;
  }
}
</style>