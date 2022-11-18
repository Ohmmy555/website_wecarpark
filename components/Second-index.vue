<template>
    <div class="second-page">
      <div class="features">
        <div class="topic_t">Please be assured that</div>
        <feature-item
          v-for="(item, index) in items"
          :key="index"
          :loading="loading"
          :item="item"
        />
      </div>
    </div>
  </template>
  
  <script>
  import FeatureItem from "./FeatureItem.vue";
  export default {
    components: { FeatureItem },
    data() {
      return {
        loading: false,
        items: [
          {
            topic: "Security",
            des: "We have CCTV to monitor security and check parking spaces to show the parking status if there is a parking space or not.",
            img: "cctv.svg",
          },
          {
            topic: "Search",
            des: "You can find a lot of parking spaces. Convenient because our application has collected parking spaces all over the country. no matter where You can find parking easily.",
            img: "magnifying-glass.svg",
          },
          {
            topic: "Privacy",
            des: "You can be confident that your information will be kept confidential and secure. No one else can extract your information.",
            img: "shield.svg",
          },
        ],
      };
    },
    methods: {
      mouseMove() {
        this.loading = true;
      },
    },
  };
  </script>
  
  <style scoprd>
  .second-page {
    display: flex;
    justify-content: center;
    width: 100vw;
    min-height: 50vh;
    background-color: rgb(249, 251, 252);
  }
  
  .features {
    width: 1200px;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    padding-top: 3rem;
    padding-bottom: 3rem;
    justify-items: center;
  }
  
  .topic_t {
    font-size: 2rem;
    font-weight: 400;
    grid-column: 1 / span 3;
    grid-row: 1;
    margin-bottom: 2rem;
  }

  .icon{
    width: 4rem;
  }
  
  @media only screen and (max-width: 992px) {
  }
  
  @media only screen and (max-width: 768px) {
  }
  
  @media only screen and (max-width: 576px) {
    .features {
      display: inline;
    }
    .second-page{
      display: block;
    }
    .topic_t{
      font-size: 1.5rem;
      text-align: center;
      padding-top: 2.5rem;
    }
  }
  </style>