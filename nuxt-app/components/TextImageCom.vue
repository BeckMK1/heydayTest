<template>
  <div class="{{imageFilp}}">
    <div>
        <p>{{problem}}</p>
        <h3>{{title}}</h3>
        <p>{{content}}</p>
    </div>
    <div>
        <img src="{{image}}" alt="">
    </div>
  </div>
</template>

<script>
export default {
props:{
    problem:String,
    title:String,
    content:String,
    image:String,
    imageFlip:String
}
}
</script>

<style>

</style>