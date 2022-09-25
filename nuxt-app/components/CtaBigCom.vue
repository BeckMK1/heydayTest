<template>
  <div class="bigCtaContainer" :class="addedborder">
    <div class="iconContaier">
        <img :src="icon" alt="">
        <p>{{title}}</p>
    </div>
      <h2>How much can<span class="Heighlight">your country</span>save with refour?</h2>
    <div class="buttonContainer">
    <button>read more</button>
  </div>
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
    background:#FF6F3D ;
    padding: 0;
    border:none;
    color:white;
    border-radius: 8px;
    font-size: 16px;
    text-transform: uppercase;
    font-weight: 600;

}
.buttonContainer{
  width: fit-content;
  margin: 32px auto 0 auto;
  
}
.buttonContainer:hover{
  border:dashed #FF6F3D 2px;
  padding: 2px;
  border-radius: 8px;
  transition: 200ms ease;
  margin: 40px auto 0 auto;
  button{
    transition: 200ms ease;
  width: 160px;
  height: 50px;
}
}
.Heighlight {
  color:#FF6F3D;
  margin: 0 4px;
  display: inline;
}
h2{
  text-align: center;
  text-transform: uppercase;
}
}
.iconContaier{
  display: flex;
  flex-direction: column;
  align-items: center;
  gap:31px;
  p{
    color:#FF6F3D;
    margin-bottom: 24px;
    font-size: 16px;
    font-weight: bold;
  }
}
@media(max-width:1024px){
  .bigCtaContainer{
    height: 400px;
  }
}
</style>