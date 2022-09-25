<template>
  <div class="pageContainer">
    <img :src="image" alt="">
  </div>
</template>

<script>
export default {
props:{
    image:String
}
}
</script>

<style lang="scss" scoped>
div{
  width: 100%;
  display: flex;
  justify-content: center;
  margin: 0 auto;
    padding-top: 172px;
}
</style>