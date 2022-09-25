<template>
  <footer>
    <div class="mainFooter container">
    <div class="contact">
        <img class="logo" src="../Assets/icons/Logo.svg" alt="">
        <div class="footRow">
            <img src="../Assets/icons/phone.svg" alt="">
            <p>+45 50 80 20 99</p>
        </div>
        <div class="footRow">
            <img src="../Assets/icons/mail.svg" alt="">
            <p>info@refour.com</p>
        </div>
        <div class="footRow">
            <img src="../Assets/icons/adress.svg" alt="">
            <p>Nikolaj Plads 15 1067 <br> København K <br> CVR: 54786214</p>
        </div>
    </div>
    <div class="footCol">
        <h3>Genveje</h3>
        <a href=""><img src="../Assets/icons/link.svg"> Sustainability</a>
        <a href=""><img src="../Assets/icons/link.svg">Material</a>
        <a href=""><img src="../Assets/icons/link.svg">End application</a>
        <a href=""><img src="../Assets/icons/link.svg">cost</a>
        <a href=""><img src="../Assets/icons/link.svg">About</a>
        <a href=""><img src="../Assets/icons/link.svg">FAQ</a>
        <a href=""><img src="../Assets/icons/link.svg">Contact</a>
    </div>
    <div class="footCol">
        <h3>Andre links</h3>
        <a href=""><img src="../Assets/icons/link.svg">How much can your country save?</a>
        <a href=""><img src="../Assets/icons/link.svg">How much can your company save?</a>
        <a href=""><img src="../Assets/icons/link.svg">Press releases</a>
        <a href=""><img src="../Assets/icons/link.svg">Documentation</a>
        <a href=""><img src="../Assets/icons/link.svg">Style sheet</a>
    </div>
    <div class="footCol">
        <h3>Find os</h3>
        <div class="footRow">
        <a href=""><img src="..//Assets/icons/some-fb.svg"></a>
        <a href=""><img src="../Assets/icons/some-tw.svg"></a>
        <a href=""><img src="../Assets/icons/some-ig.svg"></a>
        <a href=""><img src="../Assets/icons/some-yt.svg"></a>
        </div>
    </div>
</div>
    <div class="subFooter">
        <div class="container">
       <a><img src="../Assets/icons/link.svg">Persondata & cookies</a>
    </div>
    </div>
</footer>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
footer{
background-color: #404041;
p,a{
    font-size: 16px;
}
}
.container{
    max-width: 1542px;
    margin:0 auto;
    background-color: #404041; 
}
.mainFooter{
    display: flex;
    justify-content: space-between;
    padding-top: 87px;
    padding-bottom: 77px;
    .logo{
        margin-bottom: 52px;
    }
    p{
        color: white;
    }
    h3{
        margin-bottom: 52px;
        color: white;
    }
    a{
        text-decoration: none;
        margin-bottom: 18px;
        color: white;
        img{
            margin-right: 8px;
        }
    }
    .contact{
        display: flex;
        flex-direction: column;
        .footRow{
        margin-bottom: 19px;
    }
    .footRow:last-child{
        align-items: flex-start;
        margin-top: 22px;
    }
    }
    .footCol{
        display: flex;
        flex-direction: column;
    }
    .footRow{
        display: flex;
        gap:8px;
        align-items: center;

    }
}
.subFooter{
    padding: 32px 0 25px 0;
    border-top: dashed 2px rgba(255,255,255, 0.5);
       a{
        color:rgba(255,255,255, 0.5);
        img{
            margin-right: 18px;
        }
       } 
    }
</style>