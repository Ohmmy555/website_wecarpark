<template>
  <div>
    <Navbar/>   
<div class="container-fluid p-3 alert-success">
  <p class="text-center text-warm"><b><span class="topic_we">We</span><span class="topic_carpark">Carpark</span></b> กำลังอยู่ในช่วงการทดสอบที่คณะศึกษาศาสตร์ มหาวิทยาลัยขอนแก่น</p>
</div>
  <div class="container">
    <div class="left">
    <h1 class="text-center topic mt-4"><span class="topic_we">Easy Park</span><br><span class="topic_carpark">Easy Pay</span></h1>
    <p class="des text-center">A platform that lets parking space owners rent out their spaces to drivers looking for a place to park.</p>
    <div class="btn-download">
      <a href="/">
      <button type="button" class="btn btn-success"><img src="../assets/icon/android.svg" alt="logo android" class="icon-android">Download for Android</button>
    </a>
    </div>
    
  </div>

  <div class="right">
    <img src="../assets/image/index_app.svg" alt="" class="img-phone-index">
  </div>

  </div>
</div>
</template>

<script>
export default {

}
</script>
<style>
.topic_we{
    color: #fd9509;
}

.topic_carpark{
    color: #11833a;
}

.btn{
  border-radius: 15px;
  padding: 0.7rem;
}

.icon-android{
  width: 1.8rem;
  margin-right: 0.4rem;
}

@media screen and (min-width: 360px) {
  .topic{
    font-size: 3rem;
    font-weight: 400;
  }

  .text-warm{
    font-size: 0.7rem;
    margin-bottom: 0;
  }

  .des{
    font-size: 0.7rem;
    font-weight: 300;
    margin: 1rem 0;
  }

  .btn-download{
text-align: center;
  }

  .img-phone-index{
    width: 10rem;
margin: auto auto;
display: block;
  }

  .right{
    margin: 1rem 0;
  }
}
</style>