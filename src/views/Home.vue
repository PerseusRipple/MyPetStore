<template>
  <div class="wrapper">
    <div class="panel tall-panel light-mint">
      <h2>Pet Products</h2>
      <p>Premium Puppy Chow</p>
      <p>Kibble, sale in bulk, $20/lb</p>
      <img
        src="https://raw.githubusercontent.com/VueVixens/projects/master/petshop/images/food.png"
      >
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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
