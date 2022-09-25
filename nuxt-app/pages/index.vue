<template>
  <div>
    <div class="fixedIcon">
    <div class="icon">
    <img class="mainIcon" src="../Assets/icons/icon-earth.svg" alt="">
    </div>
    <div class="hoverHidden">
      <div class="iconContainer">
      <div class="textHeighlight">
      <p>Lorem</p><p>ipsum dolar sit</p>
      </div>
      <div class="iconCol">
        <div> <img src="../Assets/icons/icon-trees.svg"><p>Trees cut down this year</p></div>
        <span>152.124.156</span>
      </div>
      <div class="iconCol">
        <div> <img src="../Assets/icons/icon-co2.svg"><p>CO2 emissions this year</p></div>
        <span>254.241.245</span>
      </div>
    </div>
    </div>
    </div>
    <BannerCom></BannerCom>
    <div class="">
      <div class="flexConteinerTextBar pageContainer">
      <TextCtaCom size="half" title="Putting our health and planet first" content="Refour is more than packaging. We are the greenest solution on the planet, paving a path towards a better future. With the lowest cost and the best performing features, we put a, sustainable material into reach of all corporations that want to act now to help restore and renew our planet. We are not paper, nor plastic, and we do not mix materials. We are 100% recyclable."></TextCtaCom>
      <div class="barContainer">
        <BarCom title="Recyleble" amountText="100%" amount="width:100%"></BarCom>
        <BarCom title="Lower carbon footprint" amountText="80%" amount="width:80%"></BarCom>
        <BarCom title="Lower cost" amountText="60%" amount="width:60%"></BarCom>
        <BarCom title="Less material-user" amountText="50%" amount="width:50%"></BarCom>
      </div>
      </div>
    </div>
      <FullVideoCom></FullVideoCom>
      <FullImage image="../Assets/gif-placeholder.png"></FullImage>
  <div class="sectionBorder">
    <div class="flexConteinerCta pageContainer">
      <CtaShortCom title="Sustainability" excerpt="Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua." conte coverImage="cover" image="../Assets/card-1.png"></CtaShortCom>
      <CtaShortCom title="Material" excerpt="Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua." coverImage="cover"  image="../Assets/card-2.png"></CtaShortCom>
    <CtaShortCom title="End application" excerpt="Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua." image="../Assets/card-3.png"></CtaShortCom>
    <CtaShortCom title="Cost" excerpt="Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua." coverImage="cover" image="../Assets/card-4.png"></CtaShortCom>
  </div>
  </div>
  <div class="sectionBorder">
  <FullQuotes name="Kildens navn" content="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin diam purus, lacinia vitae tortor ut, mollis tincidunt urna."></FullQuotes>
  </div>
  <div class="sectionWidth">
    <div class="flexConteinerBigCta pageContainer">
    <CtaBigCom addedborder="border" icon="../Assets/icons/config_1.svg" title="Sustainability"></CtaBigCom>
    <CtaBigCom icon="../Assets/icons/config_2.svg" title="Material"></CtaBigCom>
    </div>
  </div>
  <CtaContactCom title="Do you have any questions?" content="Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy" Cta="Contact us"></CtaContactCom>
</div>
</template>

<style lang="scss">
  .textHeighlight {
    display: flex;
    justify-content: center;
    h2:nth-child(2){
      color:#FF6F3D;
    margin-right: 4px;
    margin-left: 4px;
    }
    p:first-child{
    color:#FF6F3D;
    margin-right: 4px;
  }

  }
  .fixedIcon{
    position: fixed;
    right: 50px;
    bottom: 100px;
    width: 350px;
    height: 400px;
    display: flex;
    align-items: flex-end;
    z-index: 3;
    .mainIcon{
      position: absolute;
        right: 20px;
        border: 2px dashed #FF6F3D;
            padding: 5px 5px;
            border-radius: 100%;
            width: 40px;
    }
  }
.hoverHidden{
  opacity: 0;
  max-height: 306px;
  height: 250px;
  width: 388px;
  margin-block: 20px;
  transition: 500ms ease;
  background-color: white;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  z-index: 3;
  position: relative;
  border:dashed 2px #4040411A;
  border-radius: 8px;
  .iconContainer{
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    height: 80%;
    width: 80%;
    p{
      text-transform: uppercase;
      font-size: 14px;
      font-weight: bold;
    }
    .iconCol{
      div{
        display: flex;
        align-items: center;
        font-weight: 600;
        gap: 8px;
        margin-bottom: 8px;
        p{
          font-size: 16px;
          text-transform: uppercase;
          color:#6E6E6D;
        }
      }
      span{
          font-size: 40px;
          font-weight: 500;
        }
    }
  }

}
.icon{
  z-index: 99;
}
.icon:hover{
.mainIcon{
  padding:10px 10px;
  transition: 200ms ease;

}
}
.icon:hover + .hoverHidden{
  opacity: 1;
  height: 306px;
  transition: 500ms ease;
}
.flexConteinerTextBar{
  display: flex;
  gap: 32px;
  padding-bottom: 172px;
    padding-top: 172px; 
}
.flexConteinerCta{
  display: flex;
  gap:32px;
  width:100%;
}
.flexConteinerBigCta{
  display: flex;
  justify-content: space-between;
}
.border{
  border-right: dashed 2px #3737fc1a;
  width: 50%;
  height: 100%;
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
  .sectionBorder{
    padding-bottom: 172px;
    padding-top: 172px;
    border-bottom: dashed 2px #4040411A;
  }
  .sectionWidth{
    border-bottom: dashed 2px #4040411A;
    height: 656px;
  }
  @media(max-width:1024px){
    .flexConteinerTextBar{
      flex-direction: column;
      align-items: center;
      .barContainer{
      width: 80%;
      
      }
    }
    .flexConteinerCta{
      flex-direction: column;
      align-items: center;
      .flexCol{
        display: flex;
      }
    }
    .sectionWidth{
      height: 100%;
    }
    .flexConteinerBigCta{
      flex-direction: column;
      
      align-items: center;
      gap: 32px;
      .border{
        border:none;
      }
    }
  }
</style>