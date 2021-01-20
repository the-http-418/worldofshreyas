<template>
  <div class="hello">
    <img id="heropic" alt="Shreyas Dabbing" src="../assets/shreyasDab.jpg"/>
    <h1>Hi guys, I'm Shreyas!</h1>
    <h2>I'm a Gamer, YouTuber and Rising Star!</h2>
    <h2>Make sure you subscribe to my channel</h2>
    <div class="g-ytsubscribe" data-channelid="UC9WOO_wtTl2OKLl-UtYjzfg" data-layout="full" data-count="default"></div>
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
  },
  mounted() {
    let externalScript = document.createElement('script')
    externalScript.setAttribute('src', 'https://apis.google.com/js/platform.js')
    document.head.appendChild(externalScript)
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#heropic {
  max-width: 50%;
}
.hello{
  text-align: center;
  padding-bottom: 5%;
}
</style>
