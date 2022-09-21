<template>
  <div>
    <div class="title">
        <p>{{title}}</p>
        <span>{{amountText}}</span>
    </div>
    <div class="bar">
        <div class="barAmount" style="width={{amount}}%"></div>
    </div>
  </div>
</template>

<script>
export default {
props:{
 title:String,
 amountText:String,
 amount:Number
}
}
</script>

<style>

</style>