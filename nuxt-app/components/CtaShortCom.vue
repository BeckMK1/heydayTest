<template>
  <div>
    <img src="{{image}}" alt="">
    <div>
        <h3>{{title}}</h3>
        <img src="../Assets/icons/CTA-arrow.svg" alt="">
    </div>
    <p>{{excerpt}}</p>
  </div>
</template>

<script>
export default {
props:{
    title:String,
    excerpt:String,
    image:String
}
}
</script>

<style>

</style>