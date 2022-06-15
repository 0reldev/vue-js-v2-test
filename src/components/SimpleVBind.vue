<template>
  <div class="simple-v-bind" id="simple-v-bind">
    <hr>
    <h2>Liaison d'attributs avec la directive v-bind</h2>
    <span v-bind:title="message">
    Passer la souris sur ce texte pendant quelques secondes pour voir le titre dynamique.
    </span>
  </div>
</template>

<script>

export default {
  name: 'SimpleVBind',
  props: {
    message: String
  }
}

</script>

<style scoped>
.simple-v-bind {
  margin: 5em 0;
}
</style>
