<template>
  <div>
    <div>
      <b-container>
        <b-col>
          <Header />
          <b-row>
            <HelloWorld />
          </b-row>
        </b-col>
      </b-container>
    </div>

  <!-- <login /> -->
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import Header from "./components/common/header.vue";
// import login from "./views/login-page.vue"

export default {
  name: "App",

  components: {
    HelloWorld,
    Header,
    // login
  },

  data: () => ({
    //
  }),
};
</script>

<style>
.container {
  height: 100%;
}
</style>
