<script>
export default {

}
</script>

<template>
  <footer>
    <div class="container-infos">
      <div class="infos">
        <div class="info">
          <img src="../assets/img/buy-comics-digital-comics.png" alt="">
          <span>DIGITAL COMICS</span>
        </div>
        <div class="info">
          <img src="../assets/img/buy-comics-merchandise.png" alt="">
          <span>DIGITAL COMICS</span>
        </div>
        <div class="info">
          <img src="../assets/img/buy-comics-subscriptions.png" alt="">
          <span>DIGITAL COMICS</span>
        </div>
        <div class="info">
          <img src="../assets/img/buy-comics-shop-locator.png" alt="">
          <span>DIGITAL COMICS</span>
        </div>
        <div class="info">
          <img class="special" src="../assets/img/buy-dc-power-visa.svg" alt="">
          <span>DIGITAL COMICS</span>
        </div>
      </div>
    </div>

    <div class="container-specs">
      <div class="container">
        <div class="specs">
        <ul>
          <li class="subtitle">DC COMICS</li>
          <li>Charaters</li>
          <li>Comics</li>
          <li>Movies</li>
          <li>TV</li>
          <li>Games</li>
          <li>Videos</li>
          <li>News</li>
          <li class="subtitle">SHOP</li>
          <li>Shop DC</li>
          <li>Shop DC Collectibles</li>
        </ul>

        <ul>
          <li class="subtitle">DC</li>
          <li>Terms Of Use</li>
          <li>Privacy policy (New)</li>
          <li>Ad Choices</li>
          <li>Advertising</li>
          <li>Jobs</li>
          <li>Subscriptions</li>
          <li>Talent Workshops</li>
          <li>CPSC Certificates</li>
          <li>Ratings</li>
          <li>Shop Help</li>
          <li>Contact Us</li>
        </ul>

        <ul>
          <li class="subtitle">SITES</li>
          <li>DC</li>
          <li>MAD Magazine</li>
          <li>DC Kids</li>
          <li>DC Universe</li>
          <li>DC Power Visa</li>
        </ul>

        
        </div>

        <div class="dc-logo">
        <img src="../assets/img/dc-logo-bg.png" alt="">
        </div>
      </div> 
    </div>

    <div class="socials">
      <div class="container">
        <button>SIGN UP NOW!</button>
        <div class="platforms">
          <span>FOLLOW US</span>
          <img src="../assets/img/footer-facebook.png" alt="">
          <img src="../assets/img/footer-twitter.png" alt="">
          <img src="../assets/img/footer-youtube.png" alt="">
          <img src="../assets/img/footer-pinterest.png" alt="">
          <img src="../assets/img/footer-periscope.png" alt="">
        </div>
      </div>
    </div>
  </footer>
</template>


<style lang="scss" scoped>

.container-infos{
  background-color: rgba(2,130,249,255);
  height: 150px;
  display: flex;
  align-items: center;
  z-index: 6;
  .infos{
    display: flex;
    gap: 2em;
    width: 70%;
    margin-inline: auto;
  }
}

.info {
  display: flex;
  align-items: center;
  gap: 1em;
  color: white;
  
  img{
    height: 70px;
  }

  .special{
    height: 50px;
  }

}



.container-specs{
  background-image: url(../assets/img/footer-bg.jpg);
  height: 300px;
  padding: 3em;
  
  .container{
    width: 80%;
    margin-inline: auto;
    display: flex;
    justify-content: space-between;
  }
  
  .specs{
    width: 30%;
    display: flex;
    ul{
      list-style: none;
      color: white;
      margin-right: 1em;
      
      li{
        font-size: .6em;
        color: rgb(167, 161, 161);
        margin-top: .5em;
      }

      .subtitle{
          color: white;
          font-size: 1.1em;
          font-weight: bold;
          margin-bottom: .5em;
        }
    }
  } 
}


.dc-logo{
  width: 50%;
  height: 100%;
  position: relative;
  
  img{
    width: 450px;
    position: absolute;
    top: -120px;
  }
}



.socials{
  height: 100px;
  background-color: rgba(48,48,48,255);
  

  
  .container{
    width: 70%;
    height: 100%;
    margin-inline: auto;
    align-items: center;
    display: flex;
    justify-content: space-between;

      button{
      padding: 1em;
      border: 2px solid rgba(2,130,249,255);
      background-color: rgba(48,48,48,255);
      color: white;
      height: 50px;
    }

      .platforms{
      display: flex;
      align-items: center;
      gap: 1em;
      color: rgba(2,130,249,255);
    }
  }
}


</style>