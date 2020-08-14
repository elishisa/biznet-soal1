<template>
  <!-- <div id="app">
    <upperHeader></upperHeader>
  </div>-->
  <section>
    <div>
      <header class="header trans_300" style="z-index: 999;">
        <upperHeader />
        <mainDashboard :showModal="(id) => showModal(id)" />
        <modalView
          id="exampleModal"
          :showModal="(id) => showModal(id)"
          :hideModal="(id) => hideModal(id)"
        />
      </header>
    </div>
  </section>
</template>

<script>
import upperHeader from "./components/upperHeader.vue";
import mainDashboard from "./components/main-dashboard.vue";
import modalView from "./components/modal.vue";

export default {
  name: "App",
  components: {
    upperHeader,
    mainDashboard,
    modalView,
  },
  methods: {},
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
