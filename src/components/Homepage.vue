<template>
  <div class="hello">
    <img id="heropic" alt="Shreyas Dabbing" src="../assets/shreyasDab.jpg"/>
    <h1>Hi guys, I'm Shreyas!</h1>
    <h2>
       I play various games like Among Us, Roblox and more!
    </h2>
    <h3>
      Subscribe my channel to receive updates
    </h3>
  </div>
</template>

<script>
export default {
  name: 'Homepage',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#heropic {
  max-width: 50%;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
