<template>
  <div>
    <b-container>
      <h1 class="text-center mt-3">{{ title }}</h1>
    </b-container>
  </div>
</template>

<script>
export default {
  name: "MainTitle",
  data() {
    return {
      title: "Lista de Frutas"
    };
  }
};
</script>

<style scoped>
h1 {
  font-size: 50px;
  font-weight: 600;
  color: #FA8072;
  font-family: "Poiret One", cursive;
}
</style>