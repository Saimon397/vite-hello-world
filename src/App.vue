<template>
  <div class="my-jumbo">
    <h1><img src="/favicon.ico" alt="logo-vue"> {{ text }}</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      text: "La mia prima app con Vite!"
    }
  }
}
</script>

<style lang="css" scoped>
.my-jumbo {
  background-image: url(../img/1134392.png);
  height: 100vh;
}

h1 {
  text-align: center;
  font-size: 45px;
  font-style: oblique;
  padding: 300px;
  color: white;
  font-weight: bold;
}
</style>