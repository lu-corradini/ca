<template>
  <HeaderComponent/>
  <MainComponent/>
</template>

<script>
import HeaderComponent from "./components/HeaderComponent.vue";
import MainComponent from "./components/MainComponent.vue";

export default {
  name: "App",
  components: {
    HeaderComponent,
    MainComponent
  },
};
</script>

<style>
  *{
    margin: 0;
    padding: 0;
  }
</style>
