<template>
 <div class="jumbo-image">
  <div class="jumbo-text">
    <h2 class="jumbo-title">Questa è la jumbo di andrea</h2>
    <p>Pragrafo e qualcosa da scrivere a caso</p>
  </div>
</div>
</template>

<script>
export default {
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.jumbo-image{
  margin: auto;
  background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(https://nobleorderbrewing.com/img/lists/63/naruto-10-most-powerful-summoning-animals-8.jpg);
  height: 500px;
  max-width: 1200px;
  display: flex;
  justify-content: center;
}
.jumbo-text{
  
  color: rgb(251, 194, 4);
  margin: 2rem;
}
.jumbo-text{
  font-size: 2rem;
}
</style>
