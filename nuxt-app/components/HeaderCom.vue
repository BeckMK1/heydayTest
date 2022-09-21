<template>
  <header>
    <div class="logo"> <img src="../Assets/icons/Logo.svg" alt=""></div>
    <nav class="menu">
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
}
</style>

