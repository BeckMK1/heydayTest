<template>
  <div class="half">
    <h3>{{title}}</h3>
    <p class="content">{{content}}</p>
    <a class="readMore" href="{{link}}">
            <p>Read more</p>
            <img src="../Assets/icons/CTA-arrow.svg" alt="">
        </a>
  </div>
</template>

<script>
export default {
props: {
title: String,
content: String,
link:String,
size:String
}
}
</script>

<style lang="scss" scoped>
.half{
  width: 50%;
  margin-right: 12px;
  h3{
    text-transform: uppercase;
    margin-bottom: 12px;
  }
  .content{
    width: 75%;
  }
  .readMore{
  p{
    font-size: 16px;
  }
  }
}
</style>