<template>
  <div> 
  <div class="container-fluid p-3 alert-success">
    <p class="text-center text-warm"><b><span class="topic_we">We</span><span class="topic_carpark">Carpark</span></b> กำลังอยู่ในช่วงการทดสอบที่คณะศึกษาศาสตร์ มหาวิทยาลัยขอนแก่น</p>
  </div>
    <div class="container download">
      <div class="left-download">
      <h1 class=" topic mt-4"><span class="topic_we">Easy Park</span><br><span class="topic_carpark">Easy Pay</span></h1>
      <p class="des">A platform that lets parking space owners rent out their spaces to drivers looking for a place to park.</p>
      <div class="btn-download">
        <a href="https://install.appcenter.ms/users/panuwat_ys-kkumail.com/apps/wecarpark/distribution_groups/public?fbclid=IwAR0P04_MtB6rGBv_JB74WXdeSQwlww2wvoKBHAOGn6QX_29rNfb-q6Tu7AA" target="_blank" class="">
        <button type="button" class="btn"><img src="../assets/icon/android.svg" alt="logo android" class="icon-android">Download for Android</button>
      </a>
        <a href="#how" class="des-how-a">
        <p class="des-how">Steps and how to download</p>
      </a>
      </div>
      <div class="contact">
        <p class="des"><a href="https://line.me/ti/p/%40wecarpark#~" target="_blank" class="link-line-contact"><img src="../assets/icon/line.svg" alt="icon line" class="icon-contact"> @wecarpark</a></p>
      </div>
  
    </div>
  
    <div class="right-download">
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
    background: #11833a;
    color: white;
  }
  
  .btn:active{
    background: white;
    color: #11833a;
  }
  
  .icon-android{
    width: 1.8rem;
    margin-right: 0.4rem;
  }
  
  .icon-download{
    width: 1.5rem;
  }

  .link-line-contact{
    text-decoration: none;
    color: black;
  }

  .des-how{
    color: #fd9509;
    margin: auto;
  }

  .des-how-a{
    margin: auto;
    margin-left: 0;
  }

  .btn-download{
    color: #fff;
  }

  .btn-download:hover{
color: #fff;
  }
  
  @media screen and (max-width: 450px) {
    .topic{
      font-size: 3rem;
      font-weight: 400;
      text-align: center;
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
      padding-bottom:2rem ;
    }
  
    .right{
      margin: 1rem 0;
    }
  
    .des-how{
      margin-top: 1rem;
      text-align: center;
      font-size: 0.8rem;
      color: #fd9509;
    }

    .icon-contact{
        width:2rem;
      }

      .des{
        text-align: center;
      }


  }
    @media (max-width: 576px) {
      .img-phone-index{
        width: 14rem;
        padding: 0;
      }
      .icon-contact{
        width: 1.4rem;
      }
  }

    @media (max-width: 768px) {
      .img-phone-index{
        width: 16rem;
        padding: 0;
      }
      .icon-contact{
        width: 1.8rem;
      }
  }

    @media (max-width: 992px) {

      .img-phone-index{
        width: 18rem;
        padding: 0;
      }
      .icon-contact{
        width: 2rem;
      }

  }

    @media (min-width: 1200px) {
      .download{
        display: flex;
      }

      .right-download{
        margin-top: 0;
        margin: auto;
        display: flex;
        height: 90vh;
      }

      .img-phone-index{
        width: 20rem;
        padding: 0;
      }

      .left-download{
        display: block;
        margin: auto;
      }

      .btn-download{
        display: flex;
        margin-top: 3rem;
      }

      .des-how{
        margin-left: 1rem;
      }

      .topic{
        font-size: 4rem;
      }

      .des{
        font-size: 0.9rem;
        margin: 0;
      }

      .contact{
        margin-top: 1rem;
      }

      .icon-contact{
        width: 2rem;
      }

      .text-warm{
      font-size: 0.9rem;
      margin-bottom: 0;
    }
  }
</style>