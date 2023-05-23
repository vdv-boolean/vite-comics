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
@use './../assets/styles/partials/variables' as *;
.container-infos{
  position: relative;
  background-color: $brand-color;
  height: 150px;
  @include align-center;
  .infos{
    display: flex;
    gap: 2em;
    width: 70%;
    margin-inline: auto;
  }
}

.info {
  @include align-center;
  gap: 1em;
  color: $base-color;
  white-space: nowrap;
  
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
  display: flex;
  
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
      color: $base-color;
      margin-right: 1em;
      
      li{
        font-size: .6em;
        cursor: pointer;
        color: rgb(167, 161, 161);
        margin-top: .5em;
        &:hover{
          text-decoration: underline;
        }
      }

      .subtitle{
          color: $base-color;
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
  @include align-center;
  
  img{
    width: 450px;
  }
}

.socials{
  position: relative;
  height: 100px;
  background-color: $brand-color-dark;
  
  .container{
    width: 70%;
    height: 100%;
    @include align-justify-center;
      button{
      padding: 1em;
      border: 2px solid $brand-color;
      background-color: $brand-color-dark;
      color: $base-color;
      height: 50px;
      cursor: pointer;
      &:active{
        background-color: grey;
      }
    }

      .platforms{
      @include align-center;
      gap: 1em;
      color: $brand-color;
    }
  }
}
</style>