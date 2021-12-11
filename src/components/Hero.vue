<template>
  <div class="jumbo">
    <h3>Jumbotron Vue</h3>
  </div>
</template>


<script>
export default {
  name: "Hero",
};
</script>


<style scoped>
.jumbo {
    height: 400px;
    background-image: url(../assets/vueimg.png);
    background-size: cover;
    background-position: center;

    display: flex;
    justify-content: center;
    align-items: center;
}

h3 {
    font-size: 25px;
}

</style>
