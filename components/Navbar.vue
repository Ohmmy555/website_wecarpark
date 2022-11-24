<template>
  <div class="container">
  <b-navbar toggleable="lg" variant="white" class="p-2 mb-6 bg-body rounded">
    <b-navbar-brand href="/" class="pl-3"><span class="brand_we">We</span><span class="brand_carpark">Carpark</span></b-navbar-brand>

    <b-navbar-toggle target="nav-collapse" class="pr-3"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav class="ml-auto">
        <b-nav-item href="/" class="item-one">Home</b-nav-item>
        <b-nav-item href="download" class="item-one" style="margin-right:1.5rem;">Download</b-nav-item>
        <div class="menu">
        <a href="https://www.facebook.com"><img src="../assets/icon/facebook.svg" alt="" class="icon-contact" style="margin-right: 1rem;"></a>
        <a href="https://line.me/ti/p/%40wecarpark#~"><img src="../assets/icon/line.svg" alt="" class="icon-contact" style="margin-right: 1rem;"></a>
        <a href="https://www.instagram.com"><img src="../assets/icon/instagram.svg" alt="" class="icon-contact" style="margin-right: 1rem;"></a>
        <a href="https://www.twitter.com"><img src="../assets/icon/twitter.svg" alt="" class="icon-contact" style="margin-right: 1rem;"></a>
      </div>
      </b-navbar-nav>

    </b-collapse>
  </b-navbar>
</div>
</template>

<script>
export default {

}
</script>

<style>

.brand_we{
    color: #fd9509;
    font-size: 20px;
}

.brand_carpark{
    color: #11833a;    
    font-size: 20px;
}

.container{
  z-index: 20;
}

.menu{
      padding-left: 1rem;
      margin: 0;
    }

@media screen and (min-width: 360px) {
    .item-one{
        font-size: 0.8rem;
        padding-left: 1rem;
    }

    .item-one:hover{
        color: #fd9509;
    }
    .menu{
      padding-left: 1rem;
      margin: 1rem 0;
    }
}
@media (min-width: 576px) {

}

@media (min-width: 768px) {

}

@media (min-width: 992px) {

}

@media (min-width: 1200px) {
  .navbar-class{
    width: 1000px;
    margin: auto;
  }
  .menu{
      padding-left: 0;
      margin: 0;
      padding-top: .1rem;
    }
}

@media (min-width: 1400px) {

}

</style>