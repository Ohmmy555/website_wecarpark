<template>
    <div class="">
      <img class="image-profile" :src="getImage()" alt="" />
      <br />
      <div class="item-name">{{ item.name }}</div>
      <div class="item-role">{{ item.role }}</div>
    </div>
  </template>
  
  <script>
  export default {
    props: {
      item: {
        image: "123",
        name: {
          default: "Anonymous",
          type: String,
        },
        role: "Mobile Developer",
      },
    },
    data() {
      return {
        image: { ...this.image2 },
      };
    },
    methods: {
      getImage() {
        return require(`../assets/profiles/${this.item.image}`);
      },
    },
  };
  </script>
  
  <style scoped>
  
  .image-profile {
    display: block;
    margin: 0 auto;
    width: 12rem;
    height: 12rem;
    border-radius: 100%;
    object-fit: cover;
  }
  
  .item-name,
  .item-role {
    text-align: center;
  }
  
  @media only screen and (max-width: 992px) {
    .image-profile {
      width: 12rem;
      height: 12rem;
    }
  }
  
  @media only screen and (max-width: 768px) {
    .circle {
      background-color: red;
    }
  }
  
  @media only screen and (max-width: 576px) {
    .image-profile {
      width: 5rem;
      height: 5rem;
    }
  }

  @media only screen and (max-width:400px) {
    .image-profile{
      width: 8rem;
      height: 8rem;
    }

    .item-role{
      font-size: .8rem;
    }
  }
  </style>
  