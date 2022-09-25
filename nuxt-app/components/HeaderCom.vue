<template>
  <header>
    <div class="logo"> <img src="../Assets/icons/Logo.svg" alt=""></div>
    <img class="mainNav" @click="show = !show" width="25" src="../Assets/icons/bars-solid.svg" alt="">
    <nav class="menu">
        <NuxtLink>Sustainability</NuxtLink>
        <NuxtLink>Material</NuxtLink>
        <NuxtLink>End application</NuxtLink>
        <NuxtLink>cost</NuxtLink>
        <NuxtLink>About</NuxtLink>
        <NuxtLink>FAQ</NuxtLink>
        <NuxtLink>Contact</NuxtLink>
    </nav>
    <nav v-if="show" class="menuMobil">
        <NuxtLink>Sustainability</NuxtLink>
        <NuxtLink>Material</NuxtLink>
        <NuxtLink>End application</NuxtLink>
        <NuxtLink>cost</NuxtLink>
        <NuxtLink>About</NuxtLink>
        <NuxtLink>FAQ</NuxtLink>
        <NuxtLink>Contact</NuxtLink>
    </nav>
</header>
</template>

<script>
export default {
    data(){
        return{
            show:false
        }
    }
}
</script>

<style lang="scss" scoped>
header{
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100vw;
    height: 100px;
    background-color: white;
.mainNav{
    display: none;
}
    .logo{
        width: 20%;
        margin-left:50px;
    }
    .menu{
        width: 45%;
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-right: 30px;
        font-weight: bold;
        font-size: 16px;
    }
    .menuMobil{
    display: none;
    }
}
@media(max-width:1024px){
    header{
        .menuMobil{
            display: flex;
            position:absolute;
            top:100px;
            left: 62%;
            padding: 20px;
            width: 30%;
            flex-direction: column;
            align-items: flex-end;
            background-color: white;
            gap:4px;
            cursor: pointer;
            border:dashed 2px #4040411A;
            border-top: none;
            border-radius: 0 0 8px 8px;
            font-weight: bold;
            font-size: 16px;
        }
        .menu{
            display: none;
        }
        .mainNav{
            display: block;
            margin-right: 32px;
        }
    }
}
</style>

