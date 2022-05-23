<template>
  <div>
    <div class="main-container">
      <h1>Gerenciar pedidos:</h1>
      <DashboardComponent />
    </div>
  </div>
</template>

<script>
import DashboardComponent from "../components/DashboardComponent";
export default {
  name: "Pedidos",
  components: {
    DashboardComponent,
  },
};
</script>