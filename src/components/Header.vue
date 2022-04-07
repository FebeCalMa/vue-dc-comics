<template>
  <div class="hello">
    <div class="logo">
      <img src="../img/dc-logo.png" alt="dc-logo" />
    </div>
    <div class="nav-bar">
      <ul id="nav-links">
        <li><a href="#">Lorem</a></li>
        <li><a href="#">Lorem</a></li>
        <li><a href="#">Lorem</a></li>
        <li><a href="#">Lorem</a></li>
        <li><a href="#">Lorem</a></li>
        <li><a href="#">Lorem</a></li>
        <li><a href="#">Lorem</a></li>
        <li><a href="#">Lorem</a></li>
        <li><a href="#">Lorem</a></li>
        <li><a href="#">Lorem</a></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderComponent",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.hello {
  display: flex;
  justify-content: space-around;
}
#nav-list li {
  list-style: none;
}
</style>
