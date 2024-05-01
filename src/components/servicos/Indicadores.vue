<template>
  <div>
    <h5>Componente indicadores</h5>
    <p>Poderiamos recuperar os indiadores do servico id {{ id }}</p>
  </div>
</template>
<script>
export default {
  name: "Indicadores",
  props: ["id"],
  created() {
    console.log("Indicadores", this.$route.params.id);
  },
};
</script>