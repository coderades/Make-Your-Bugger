<template>
  <BannerComponent />
  <div class="main-container">
    <h1>Monte o seu burger:</h1>
    <BurgerComponent />
  </div>
</template>

<script>
import BannerComponent from "../components/BannerComponent.vue";
import BurgerComponent from "../components/BurgerComponent.vue";

export default {
  name: "HomeComponent",
  components: {
    BannerComponent,
    BurgerComponent,
  },
};
</script>
