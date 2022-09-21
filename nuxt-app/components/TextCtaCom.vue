<template>
  <div>
    <h3>{{title}}</h3>
    <p>{{content}}</p>
    <a class="readMore" href="{{link}}">
            <p>Read more</p>
            <img src="../Assets/icons/CTA-arrow.svg" alt="">
        </a>
  </div>
</template>

<script>
export default {
props: {
title: String,
content: String,
link:String
}
}
</script>

<style>

</style>