<template>
  <div>
    <BannerCom></BannerCom>
    <div class="flexConteiner">
      <TextCtaCom size="half" title="Putting our health and planet first" content="Refour is more than packaging. We are the greenest solution on the planet, paving a path towards a better future. With the lowest cost and the best performing features, we put a, sustainable material into reach of all corporations that want to act now to help restore and renew our planet. We are not paper, nor plastic, and we do not mix materials. We are 100% recyclable."></TextCtaCom>
      <div class="barContainer">
        <BarCom title="Recyleble" amountText="100%" amount="width:100%"></BarCom>
        <BarCom title="Lower carbon footprint" amountText="80%" amount="width:80%"></BarCom>
        <BarCom title="Lower cost" amountText="60%" amount="width:60%"></BarCom>
        <BarCom title="Less material-user" amountText="50%" amount="width:50%"></BarCom>
      </div>
    </div>
    <FullVideoCom></FullVideoCom>
    <FullImage image="../Assets/gif-placeholder.png"></FullImage>
  </div>
</template>

<style lang="scss">
.flexConteiner{
  display: flex;
  gap: 32px;
}
h3{
  font-size: 30px;
}
p{
  font-size: 18px;
}
.readMore{
  margin-top: 32px;
}
</style>