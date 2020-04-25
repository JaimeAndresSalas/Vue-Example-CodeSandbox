<template>
  <div id="app" class="container">
    <div class="text-center">
      <img width="25%" alt="Vue Logo" src="./assets/logo.png">
    </div>
    <cabecera></cabecera>
    <lista></lista>
  </div>
</template>

<script>
import Cabecera from "./components/Cabecera.vue";
import Lista from "./components/Lista.vue";

export default {
  name: "App",
  components: {
    Cabecera,
    Lista
  }
};
</script>