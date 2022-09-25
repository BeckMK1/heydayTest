<template>
  <div class="half">
    <div class="title">
        <p>{{title}}</p>
        <span>{{amountText}}</span>
    </div>
    <div class="bar">
        <div class="barAmount" :style="amount"></div>
    </div>
  </div>
</template>

<script>
export default {
props:{
 title:String,
 amountText:String,
 amount:String
}
}
</script>

<style lang="scss" scoped>
.half{
  width: 50%;
  display: flex;
  flex-direction: column;
  margin-left: 12px;
  margin-bottom: 32px;
  .title{
    display: flex;
    justify-content: space-between;
    width: 35vw;
    margin-bottom: 12px;
    text-transform: uppercase;
    font-weight: bold;
    p, span{
    color:rgba(64, 64, 65, 0.5);
    }
  }
  .bar{
    width: 35vw;
    height: 5px;
    border-radius: 20px;
    background: rgba(64, 64, 65, 0.1);
    .barAmount{
      border-radius: 20px;
      background-color: #FF6F3D;
      height: 100%;
    }
  }
}
@media(max-width:1024px){
  .half{
    margin-left:auto;
    margin-right: 35%;
  }
}
</style>