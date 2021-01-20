<template>
  <div class="videos">
    <h2>Here are some of my latest videos</h2>
    <div v-for="item in urls" :key="item.url">
        <video-embedd :urlvid="'https://www.youtube.com/embed/'+item.url"/>
    </div>
  </div>
</template>

<script>
import VideoEmbedd from './VideoEmbedd.vue'
import urls from './VideoUrl.js'
export default {
  name: "Videos",
  components:{
      VideoEmbedd
  },
  data(){
      return{
          urls:urls
      }
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
