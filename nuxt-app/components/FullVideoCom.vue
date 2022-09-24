<template>
<div class="videoContainer">
  <div class="video">
    <img  src="../Assets/video-placeholder.png">
    <div>
      <img  src="../Assets/icons/icon-play.svg">
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
  margin-top: 149px;
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
</style>
