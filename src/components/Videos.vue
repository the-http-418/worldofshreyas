<template>
  <div class="videos">
    <h2>Here are some of my latest videos</h2>
    <VideoEmbedd urlvid="https://www.youtube.com/embed/6zX2ExuBcCE"/>
  </div>
</template>

<script>
import VideoEmbedd from './VideoEmbedd.vue'
import urls from './VideoUrl.js'
export default {
  name: "Videos",
  components:{
      VideoEmbedd
  }
};
console.log(urls);
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#heropic {
  max-width: 50%;
}
.video {
  margin-left: 10%;
  margin-right: 10%;
  margin-top: 5%;
  max-width: 60%;
}
.videos {
  text-align: center;
}
</style>
