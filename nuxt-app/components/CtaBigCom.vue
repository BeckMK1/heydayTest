<template>
  <div>
    <div>
        <img src="{{icon}}" alt="">
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

<style>

</style>