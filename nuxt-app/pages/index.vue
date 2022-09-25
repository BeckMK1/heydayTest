<template>
  <div>
    <BannerCom></BannerCom>
    <div class="flexConteinerTextBar">
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

  <div class="flexConteinerCta">
    <CtaShortCom title="Sustainability" excerpt="Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua." conte coverImage="cover" image="../Assets/card-1.png"></CtaShortCom>
    <CtaShortCom title="Material" excerpt="Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua." coverImage="cover"  image="../Assets/card-2.png"></CtaShortCom>
    <CtaShortCom title="End application" excerpt="Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua." image="../Assets/card-3.png"></CtaShortCom>
    <CtaShortCom title="Cost" excerpt="Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua." coverImage="cover" image="../Assets/card-4.png"></CtaShortCom>
  </div>
  <FullQuotes name="Kildens navn" content="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin diam purus, lacinia vitae tortor ut, mollis tincidunt urna."></FullQuotes>
  <div class="flexConteinerBigCta">
    <CtaBigCom icon="../Assets/icons/config_1.svg" title="Sustainability" content="How much can your country save with refour?"></CtaBigCom>
    <CtaBigCom icon="../Assets/icons/config_2.svg" title="Material" content="How much can your company save with refour?"></CtaBigCom>
  </div>
  <CtaContactCom title="Do you have any questions?" content="Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy" Cta="Contact us"></CtaContactCom>
</div>
</template>

<style lang="scss">
.flexConteinerTextBar{
  display: flex;
  gap: 32px;
}
.flexConteinerCta{
  display: flex;
  gap:32px;
  width:100%;
  margin-bottom: 172px;
}
.flexConteinerBigCta{
  display: flex;
  justify-content: space-between;
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
.cover{
    img{
      border-radius: 20px 20px 0 0;
    }
  }
</style>