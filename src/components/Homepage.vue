<template>
  <div class="hello">
    <img id="heropic" alt="Shreyas Dabbing" src="../assets/shreyasDab.jpg"/>
    <h1>Hi guys, I'm Shreyas!</h1>
  </div>
  <Videos/>
  <Games/>
</template>

<script>
import Games from './Games.vue'
import Videos from './Videos.vue'
export default {
  name: 'Homepage',
  props: {
    msg: String
  },
  components: {
    Games,
    Videos
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#heropic {
  max-width: 50%;
}
.hello{
  text-align: center;
}
</style>
