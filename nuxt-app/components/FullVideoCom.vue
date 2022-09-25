<template>
<div class="videoContainer pageContainer">
  <div class="video">
    <img class="mainImage"  src="../Assets/video-placeholder.png">
    <div>
      <img src="../Assets/icons/icon-play.svg">
    </div>
  </div>
  
</div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.videoContainer{
  height: 884px;
  border: 2px dashed #FF6F3D;
  border-radius: 43px;
  display: flex;
  justify-content: center;
  align-items: center;
  .video{
    position: relative;
    div:last-child{
      display: flex;
      justify-content: center;
      align-items: center;
      position: absolute;
      left: 50%;
      top:50%;
      z-index: 2;
      background: #FF6F3D;
      padding: 30px;
      border-radius: 100%;
      transform: translate(-50%, -50%);
    }
  }
}
@media(max-width:1024px){
  .videoContainer{
    height: 520px;
    width: 90vw;
    .mainImage{
        width: 85vw;
      }
  }
}
</style>
