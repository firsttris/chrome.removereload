<template>
  <div class="routing container-fluid">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
a {
  color: black;
}
a:hover {
  text-decoration: none;
  color: red;
}
.routing {
  margin-top: 20px;
  -webkit-touch-callout: none;
  -webkit-user-select: none;
}
.nav {
  margin-bottom: 10px;
}
.fa {
  color: red;
}
</style>
<style
  lang="css"
  src="./../../node_modules/bootstrap/dist/css/bootstrap.css"
></style>
<style
  lang="css"
  src="./../../node_modules/font-awesome/css/font-awesome.css"
></style>
