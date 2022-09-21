<template>
  <div>
    <h2>{{title}}</h2>
    <p>{{content}}</p>
    <button>{{Cta}}</button>
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

<style>

</style>