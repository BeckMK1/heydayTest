<template>
  <div class="CtaContentContainer">
    <h2>{{title}}</h2>
    <p>{{content}}</p>
    <div class="buttonContainer">
    <button>{{Cta}}</button>
  </div>
  </div>
</template>

<script>
export default {
props:{
    title:String,
    content:String,
    Cta:String
}
}
</script>

<style lang="scss" scoped>
.CtaContentContainer{
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-bottom: 141px;
  margin-top:152px ;
  h2{
    margin-bottom: 24px;
    text-transform: uppercase;
  }
  p{
    color: #6E6E6D;
  }
}

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
@media(max-width:1024px){
  .CtaContentContainer{
    p,h2{
      width: 50%;
    }
  }
}
</style>