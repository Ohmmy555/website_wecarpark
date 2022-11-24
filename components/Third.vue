<template>
    <div class="container third-class">
      <p class="topic-third"><b><span class="topic_we">We</span><span class="topic_carpark">Carpark</span></b> what do we have</p>
  <b-tabs content-class="mt-3" align="center">
    <b-tab title="Search" active :title-item-class="'tab-title-class'">

      <div class="container_third">
        <div class="img_third">
          <img src="../assets/image/index_app.svg" alt="" class="img_third_detail" />
        </div>
        <div class="content_third">
          <p class="topic_third">Find a parking space easily and conveniently</p>
          <p class="des_third">
        WeCarpark our collects the parking lot many, many styles, many prices no
        matter where you are you can search for parking spaces.
      </p>
        </div>
      </div>

    </b-tab>
    <b-tab title="Check in" :title-item-class="'tab-title-class'">
    
      <div class="container_third">
        <div class="img_third">
          <img src="../assets/image/index_app.svg" alt="" class="img_third_detail" />
        </div>
        <div class="content_third">
          <p class="topic_third">Easy in and out, safe</p>
          <p class="des_third">Get in and out of your car park comfortably and safely. Just bring the QR code to scan at our We Stand.
      </p>
        </div>
      </div>
    
    </b-tab>
    <b-tab title="Carpark detail" :title-item-class="'tab-title-class'">
    
      <div class="container_third">
        <div class="img_third">
          <img src="../assets/image/index_app.svg" alt="" class="img_third_detail" />
        </div>
        <div class="content_third">
          <p class="topic_third">Every parking lot is fully detailed</p>
          <p class="des_third">The application will show the details of the parking lot, such as the name of the car park, the price, the number of available parking spaces. Parking locations and packages All in one place
      </p>
        </div>
      </div>
    
    </b-tab>
  </b-tabs>

    </div>
  </template>
  
  <script>
  
  </script>
  
  <style>
  .third-class{
    height: auto;
  }

  .nav-link{
    color: #fea630;
  }

.tab-title-class {
    color: #fea630 !important;  
}
  .primary_color {
    color: #11833a;
  }
  
  .secondary_color {
    color: #fea630;
  }

  .color-title{
    color: #fea630;
  }
  
  .third{
      height: 90vh;
      width: 100vw;
  }
  
  .container_third{
      height: 60vh;
      width: 100%;
  display: flex;
      margin: auto;
      justify-content: center;
  }
  
  .content_third{
  margin: auto;
  }
  
  .img_third{
    margin: auto;
    display: flex;
    width: 100%;
  }
  
  .img_third_detail{
    margin: auto auto;
    height: 30rem;
  }
  
  .tag{
    color: #fea630;
    font-size: 1.1rem;
    font-weight: 400;
  }
  
  .topic_third{
    font-size: 2rem;
    font-weight: 400;
    line-height: 40px;
  }
  
  .des_third{
    font-size: 1rem;
    font-weight: 300;
    margin-top: 1rem;
  }
  
  .img_item{
    height:2rem;
  }
  
  .detail{
    display: flex;
    margin-top: 1.5rem;
  }
  
  
  .list-item {
    display: flex;
    justify-content: center;
    align-content: center;
    margin-right: 1rem;
  }
  
  
  .des-list-third{
    font-size: 1rem;
    margin-left: 0.5rem;
    margin-top: 0.2rem;
  }
  
  .topic_third_t{
    font-size: 2rem;
    font-weight: 400;
    text-align: center;
    margin-top: 2.5rem;
    margin-bottom: 2rem;
  }

  @media screen and (max-width: 450px) {

    .container_third{
      display: block;;
    }

    .topic_third_t{
      font-size: 1.1rem;
    }

    .img_third_detail{
    margin: auto auto;
    height: 20rem;
  }

  .topic_third{
    font-size: 1.3rem;
    font-weight: 400;
    line-height: -40px;
    margin-top: 1.5rem;
    text-align: center;
    color: #fea630;
    margin-bottom: 0;
  }

  .des_third{
    font-size: .7rem;
    font-weight: 200;
    text-align: center;
    margin-top: 0;
    margin-bottom: 3rem;

  }

  .container_third{
      height: auto;
      width: 100%;
  }

  .img_third{
    margin-top: 2rem;
  }

  .topic-third{
    text-align: center;
    margin: 2rem 0;

  }
  }
  </style>