<template>
    <div class="feature-item">
      <div class="circle-blog">
          <div class="image-icon">
            <img class="icon" :src="getImage()" alt="" />
          </div>
      </div>
      <div class="content">
        <div class="topic">{{ item.topic }}</div>
        <div class="des">{{ item.des }}</div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    props: {
      loading: {
        default: false,
        type: Boolean,
      },
      color: {
        default: "#000",
        type: String,
      },
      item: {
        default: {
          topic: "Function name",
          des: "lorem",
          img: "",
        },
        type: Object,
      },
    },
    data() {
      return {
        success: "circle-icon-border-success",
      };
    },
    methods: {
      getImage() {
        return require(`../assets/icon/${this.item.img}`);
      },
    },
  };
  </script>
  
  <style scoped>
  @keyframes loadingItem {
    0% {
      transform: rotate(0deg);
    }
    25% {
      transform: rotate(72deg);
    }
    50% {
      transform: rotate(144deg);
    }
    75% {
      transform: rotate(216deg);
    }
    100% {
      transform: rotate(360deg);
      border: 0.3rem solid #fea630;
    }
  }
  
  .feature-item {
  min-width: 80%;
  }
  
  .circle-blog {
    width: 100%;
    height: 5rem;
    position: relative;
    margin: auto;
  }
  
  /* .circle-icon-border {
    position: absolute;
    width: 15rem;
    height: 15rem;
    background-color: transparent;
    border-radius: 100%;
    border: 0.3rem solid transparent;
    margin: auto;
  }
  
  .circle-icon-border-success {
    position: absolute;
    width: 15rem;
    height: 15rem;
    background-color: transparent;
    border-radius: 100%;
    border-top: 0.3rem solid #fea630;
    animation: loadingItem 4s forwards;
  }
  
  .circle-icon {
    position: absolute;
    top: 0.8rem;
    left: 0.8rem;
    width: 14rem;
    height: 14rem;
    background-color: #fcd7a7;
    border-radius: 100%;
  } */
  
  .content {
    width: 19rem;
    overflow: hidden;
    text-align: center;
    margin: 0 auto;
    margin-top: 1rem;
  }
  
  .topic {
    font-size: 1.3rem;
    font-weight: 400;
  }
  
  .image-icon {
    width: 100%;
  display: flex;
  height: 2rem;
  }
  
  .icon {
    height: 5rem;
    margin: auto;
  }
  
  .des{
    margin-top: 0.5rem;
    font-weight: 300;
    font-size: 0.8rem;
    color: rgb(100, 100, 100);
  }

  
  @media only screen and (max-width: 992px) {
    .circle-icon-border-success,
    .circle-icon-border,
    .circle-blog {
      width: 10rem;
      height: 1rem;
      margin: auto;
    }
    .circle-icon,
    .image-icon {
      width: 9rem;
      height: 9rem;
    }
    .content {
      width: 10rem;
    }
  
    .icon {
      height: 3rem;
    }
  }
  
  @media only screen and (max-width: 768px) {
  }
  
  @media only screen and (max-width: 576px) {
    .content{
      width: 80%;
    }
    .image-icon {
    width: 100%;
  display: flex;
  }
  
  .icon {
    height: 12rem;
    margin: auto;
  }
  
  
  .topic {
    font-size: 1.8rem;
    height: 3rem;
    color: #fea630;
  }
  
  .des{
    margin-bottom: 3rem;
    font-weight: 400;
  }

  @media only screen and (max-width: 450px) {
    .circle-blog{
      height: auto;
    }

    .des{
      margin-bottom: 0;
    }

  }
  }
  </style>
  