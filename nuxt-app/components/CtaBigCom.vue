<template>
  <div class="bigCtaContainer" :class="addedborder">
    <div class="iconContaier">
        <img :src="icon" alt="">
        <p>{{title}}</p>
    </div>
    <h2>{{content}}</h2>
    <button>read more</button>
  </div>
</template>

<script>
export default {
props:{
    icon:String,
    content:String,
    title:String,
    addedborder:String

}
}
</script>

<style lang="scss" scoped>
.bigCtaContainer{
  display: flex;
  flex-direction: column;
  justify-content:center;
  height: 659px;
  width: 50%;
  button{
    width: 176px;
    height: 62px;
    margin: 32px auto 0 auto;
    background:#FF6F3D ;
    padding: 0;
    border:none;
    color:white;
    border-radius: 8px;
    font-size: 16px;
    text-transform: uppercase;
    font-weight: 600;

}

h2{
  text-align: center;
}
}
.iconContaier{
  display: flex;
  flex-direction: column;
  align-items: center;
  gap:31px
}
@media(max-width:1024px){
  .bigCtaContainer{
    height: 400px;
  }
}
</style>