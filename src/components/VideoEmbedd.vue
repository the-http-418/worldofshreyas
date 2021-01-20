<template>
  <iframe
    class="video"
    width="560"
    height="315"
    v-bind:src="urlvid"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen
  ></iframe>
</template>

<script>
export default {
  name: "VideoEmbedd",
  props: {
    urlvid: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
