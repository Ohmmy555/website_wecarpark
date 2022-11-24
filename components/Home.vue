<template>
  <div>
    <div class="container-fluid p-3 alert-success">
    <p class="text-center text-warm"><b><span class="topic_we">We</span><span class="topic_carpark">Carpark</span></b> กำลังอยู่ในช่วงการทดสอบที่คณะศึกษาศาสตร์ มหาวิทยาลัยขอนแก่น</p>
  </div>
    <section class="container home">
      <div class="left pl-4">
        <div class="cont-left">
        <h3 class="topic-home"><span class="we-home">We</span><span class="carpark-home">Carpark</span></h3>
        <p class="des-home">Easy Park Easy Pay</p>
        <p class="des-home-d">A platform that lets parking space owners rent out their spaces to drivers looking for a place to park.</p>
      </div>
    </div>
      <div class="right">
        <div class="cont-right">
          <img src="../assets/image/index_app.svg" alt="" class="img-index-home">
        </div>
      </div>
    </section>
  </div>
</template>
  
  <script>
export default {};
</script>
  
  <style>

.home{
  display: flex;
  height: 100vh;
}

.we-home{
  color: #fd9509;
}

.carpark-home{
  color: #11833a;
}


@media screen and (max-width: 400px) {

  .home{
    display: block;
    height: 70vh;
  }

  .text-warm{
      font-size: 0.7rem;
      margin-bottom: 0;
      margin: 0;
    }

  .img-index-home{
    width: 10rem;
      margin: auto auto;
      display: block;
      padding-bottom:2rem ;
  }

  .topic-home{
      font-size: 3rem;
      font-weight: 400;
      text-align: center;
      margin-bottom: 0;
      margin-top: 4rem;
    }

  .des-home{
    text-align: center;
    font-size: 1rem;
  }

  .des-home-d{
    text-align: center;
    font-size: 0.7rem;
      font-weight: 300;
      margin: 1rem 0;
  }

  .cont-right{
    margin-top: 4rem;
  }
}

@media (min-width: 576px) {

  .home{
  display: block;
  height: 100vh;
}

}

@media (min-width: 768px) {

}

@media (min-width: 992px) {

}

@media screen and (min-width: 1200px) {
  .topic-home{
margin-bottom: 0;
font-size: 3rem;
  }

  .des-home{
font-size: 1.8rem;
margin-bottom: 2rem;
text-align: start;
  }

  .left{
    width: 50%;
    height: 100vh;
display: flex;
  }

  .right{
    width: 50%;
    height: 100vh;
display: flex;
  }

  .img-index-home{
    width: 20rem;
    margin: auto;
  }

  .cont-left{
margin: auto;

  }

  .cont-right{
    margin: auto;
  }

  .home{
    display: flex;
  }
}

@media (min-width: 1400px) {

}

</style>
  