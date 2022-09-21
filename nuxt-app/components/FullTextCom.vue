<template>
  <div>
    <h2>{{title}}</h2>
    <p>{{subTitle}}</p>
    <p>{{content}}</p>
    <h3>{{title2}}</h3>
    <p>{{content2}}</p>
  </div>
</template>

<script>
export default {
props:{
    title:String,
    subTitle:String,
    content:String,
    title2:String,
    content2:String
}
}
</script>

<style>

</style>