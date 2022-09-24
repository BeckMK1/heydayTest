<template>
  <div>
    <div class="banner">
    <div class="text">
        <h2>Reinventing</h2>
        <h2>packaging</h2>
        <p>Introducing the most sustainable material category for packaging on the market,<br> with the lowest costs and carbon footprint to date</p>
        <a class="readMore" href="#">
            <p>Read more</p>
            <img src="../Assets/icons/CTA-arrow.svg" alt="">
        </a>
    </div>
    <div class="image">
        <img src="../Assets/Skærmbillede 2022-09-20 145806.png" alt="">
    </div>
    </div>
    <div class="icons">
    <div>
        <img src="../Assets/icons/arrow-down.svg" alt="">
    </div>
    <img src="../Assets/icons/icon-earth.svg" alt="">
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.banner{
    display: flex;
    justify-content: space-between;
    padding:120px 0;
   .text{
    p{
        font-weight: bold;
        font-size: 18px;
        
    }
    h2{
        text-transform: uppercase;
        font-size: 100px;
        font-weight: 800;
    }
    h2:last-of-type{
        color:#FF6F3D;
        margin-top:-32px;
    }
   }
   .image{
    width: 50%;
    display: flex;
    justify-content: center;
   }
}

.icons{
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-bottom: 50px;
    img:nth-child(2){
        position: absolute;
        right: 20px;
        border: 2px dashed #FF6F3D;
            padding: 5px 5px;
            border-radius: 100%;
            width: 40px;
    }
    div:first-child{
        width: 50%;
        display: flex;
        justify-content: flex-end;
        img{
            border: 2px dashed #FF6F3D;
            padding: 13px 20px;
            border-radius: 100%;
        }
    }
   }
   .readMore{
    margin-top: 56px;
   }
</style>

