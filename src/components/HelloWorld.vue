<template>
  <div class="background-img">
    <div class="row text">
      <div class="col-12">
        <h1>Pilih Jenis Kendaraan</h1>
      </div>
    </div>
    <div class="row">
      <div class="content-wrapper">
        <div class="col-6">
          <div class="img-content">
            <img src="../assets/matic.png" class="img" />
            <h2>Sepeda Motor</h2>
          </div>
        </div>
        <div class="col-6">
          <div class="img-content">
            <img src="../assets/mobil.png" class="img" />
            <h2>Mobil</h2>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Pilih Jenis Kendaraan",
  data() {
    return {
      items: [
        {
          id: 1,
          src: require("../assets/matic.png"),
        },
        {
          id: 2,
          src: require("../assets/matic.png"),
        },
      ],
    };
  },
  methods: {
    doSomething() {
      this.$router.push({ path: "/" });
    },
  },
};
</script>

<style>
.container {
  display: flex;
  height: 80vh;
  width: 100%;
  flex-direction: column;
  justify-content: center;
}

.background-img {
  height: 90vh;
  width: 100%;
  flex-direction: column;
  justify-content: center;
  background-image: url("../assets/background_home.jpg");
  background-size: cover;
  /* padding-right:0 !important */
}

.text {
  display: flex;
  /* background: blueviolet; */
  z-index: 5;
}

.img-content {
  display: flex;
  height: 100% !important;
  flex-direction: column;
  /* background: red; */
  justify-content: center;
  align-self: center;
  align-items: center;
  /* position: relative; */
}




.content-wrapper {
  display: flex;
  width: 100vh ;
  min-height: 60vh;
  flex-direction: row;
  /* background: chartreuse; */
  height: 100%;
  justify-content: center;
  align-items: center;
  align-self: center;
  /* position: relative; */
}

.img {
  display: flex;
  object-fit: contain;
  height: 40vh;
}

h1 {
  text-align: center;
  padding-top: 10px;
  color: whitesmoke;
}
h2 {
  text-align: center;
  color: whitesmoke;
}
</style>
