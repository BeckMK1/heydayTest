<template>
<div class="container">
  <NuxtLayout>
    <NuxtPage/>
  </NuxtLayout>
</div>
</template>

<script>
export default {
}
</script>

<style lang="scss">
*{
    padding: 0;
    margin: 0;
    color:#404041;
    font-family: 'Nunito Sans', sans-serif;
}
.container{
    background-color:#FBF9F4;
}
.pageContainer{
    
    max-width: 1542px;
    margin:auto;
}

.readMore{
        display: flex;
        gap: 8px;
        align-items: center;
        text-transform: uppercase;
        text-decoration: none;
        p{
        font-size: 16px;
        font-weight: 900;
        }   
    }
</style>