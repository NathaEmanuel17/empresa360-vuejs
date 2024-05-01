<template>
  <div>
    <h5>Componente Opcoes</h5>
    <p>Poderiamos recuperar as opcoes do servico id {{ id }}</p>
  </div>
</template>
<script>
export default {
  name: "Opcoes",
  props: ["id"],
  created() {
    console.log("Opçoes", this.id);
  },
  // beforeRouteUpdate(to, from, next)
  beforeRouteUpdate() {
    console.log('Guarda de componente beforeRouteUpdate')
  }
};
</script>