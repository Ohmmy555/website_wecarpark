<template>
    <section class="container home">
      <div class="left pl-4">
        <div class="cont-left">
        <h3 class="topic-home"><span class="we-home">We</span><span class="carpark-home">Carpark</span></h3>
        <p class="des-home">Easy Park Easy Pay</p>
        <p>A platform that lets parking space owners rent out their spaces to drivers looking for a place to park.</p>
      </div>
    </div>
      <div class="right">
        <div class="cont-right">
          <img src="../assets/image/index_app.svg" alt="" class="img-index-home">
        </div>
      </div>
    </section>
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

@media (min-width: 576px) {

}

@media (min-width: 768px) {

}

@media (min-width: 992px) {

}

@media (min-width: 1200px) {
  .topic-home{
margin-bottom: 0;
font-size: 3rem;
  }

  .des-home{
font-size: 1.8rem;
margin-bottom: 2rem;
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
}

@media (min-width: 1400px) {

}

</style>
  