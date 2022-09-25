<template>
  <div class="fullquotes">
    <img src="../Assets/icons/icon_quote.svg" alt="">
    <h2>{{content}}</h2>
    <div>
    <div class="name">
      <img src="../Assets/icons/quote-dash.svg" alt="">
      <p>{{name}}</p>
    </div>
    </div>
  </div>
</template>

<script>
export default {
props:{
    content:String,
    name:String
}
}
</script>

<style lang="scss" scoped>
.fullquotes{
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 164px 0;
  img{
    margin-bottom: 32px;
  }
  h2{
    text-align: center;
    width: 50%;
    margin-bottom: 40px;
  }
  .name{
    display: flex;
    gap: 8px;
    img{
      margin:0;
    }
  }
}
</style>