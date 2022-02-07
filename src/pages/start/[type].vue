<style scoped>
.wrapper {
  height: 100vh;
}
.type1 {
  background: rgb(214, 212, 54);
}
.type2 {
  background: rgb(231, 57, 26);
}
.type3 {
  background: rgb(54, 169, 214);
}
.type4 {
  background: rgb(91, 214, 54);
}
</style>

<template>
  <div class="wrapper" :class="$route.params.type">
    <RouterLink :to="'/questions/' + $route.params.type"> START </RouterLink>
  </div>
</template>

<script>
export default {};
</script>
