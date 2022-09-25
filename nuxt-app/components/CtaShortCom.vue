<template>
  <div class="ctaSize" :class="coverImage">
    <img :src="image" alt="">
    <div class="contentContainer">
    <div class="title">
        <h3>{{title}}</h3>
        <img src="../Assets/icons/CTA-arrow.svg" alt="">
    </div>
    <p>{{excerpt}}</p>
  </div>
  </div>
</template>

<script>
export default {
props:{
    title:String,
    excerpt:String,
    image:String,
    coverImage:String
}
}
</script>

<style lang="scss" scoped>
.ctaSize{
  width: 25%;
  img{
    width: 100%;
    height: 200px;
    object-fit: cover;
    margin-bottom: -4px;
  }
  .contentContainer{
  border: dashed #70707033 2px;
  border-radius:0 0 20px 20px;
  }
  .title{
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 80%;
    margin:44px auto 12px auto;
    img{
      width: 21px;
      height: 14px;
    }
  }
  p{
    width: 80%;
    margin: 0 auto;
    padding-bottom:46px ;

  }
}
.ctaSize:hover{
  transform: scale(1.05);
  transition: 500ms ease;
}
@media(max-width:1024px){
  .ctaSize{
    width: 50%;
  }

}
</style>