<template>

  <div>
    <div class="home">Home首页</div>

    <router-link to="/list">列表页</router-link>

  </div>

</template>

<script>

export default {

  name: 'Home'
}

</script>

<style scoped>

  .home{
    font-size: 30px;
    color: #990000;
  }

</style>
