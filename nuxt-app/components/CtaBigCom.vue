<template>
  <div class="bigCtaContainer">
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
    title:String
}
}
</script>

<style lang="scss" scoped>
.bigCtaContainer{
  display: flex;
  flex-direction: column;
  justify-content:center;
  margin-bottom: 161px;
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
}
.iconContaier{
  display: flex;
  flex-direction: column;
  align-items: center;
  gap:31px
}
</style>