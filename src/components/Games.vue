<template>
  <div class="games">
    <h2>Here are some of the games I play</h2>
    <img
      class="gameimg"
      src="https://cnet1.cbsistatic.com/img/bjDrQODueOs6eImEgobi_773lZM=/940x0/2020/10/21/9f706d3a-dc30-4937-8195-47aa345288e5/promofinal.jpg"
    />
    <img
      class="gameimg"
      src="https://venturebeat.com/wp-content/uploads/2017/07/roblox-1.jpg?w=1200&strip=all"
    />
  </div>
</template>

<script>
export default {
  name: "Games",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#heropic {
  max-width: 50%;
}
.gameimg {
  margin-left: 10%;
  margin-right: 10%;
  margin-top: 5%;
  max-width: 60%;
}
.games {
  text-align: center;
}
</style>
