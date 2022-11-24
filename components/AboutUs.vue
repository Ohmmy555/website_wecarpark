<template>
    <div class="about-us container">
      <div class="content">
        <div class="topic">About us</div>
        <div class="des_project">
          KKU Miss Lily Holding co., ltd. was born from the collaboration between
          Miss Lily and Khon Kaen University. In order to develop startups to be
          able to fight globally, KKU Miss Lily Digital Laboratory Startup was
          established to research and develop until it became a
          <span class="primary_color">We</span
          ><span class="secondary_color">Carpark</span>
        </div>
        <div class="profiles">
          <profile-item v-for="item in profiles" :key="item.name" :item="item" />
        </div>
      </div>
    </div>
  </template>
  
  <script>
  import ProfileItem from "./ProfileItem.vue";
  export default {
    components: { ProfileItem },
    data() {
      return {
        profiles: [
        {
            image: "MasterJ.png",
            name: "Jay",
            role: "Embedded System Engineer",
          },
        {
            image: "MasterJ.png",
            name: "Jay",
            role: "Embedded System Engineer",
          },
          {
            image: "MasterJ.png",
            name: "Jay",
            role: "Embedded System Engineer",
          },
          {
            image: "picture_geeksloth.png",
            name: "GeekSloth",
            role: "AI Researcher and Developer",
          },
          {
            image: "picture_tone.jpeg",
            name: "Tone92CS",
            role: "Backend Developer",
          },
          {
            image: "picture_k.jpeg",
            name: "KKPNW",
            role: "Frontend Developer",
          },
          { image: "picture_saiyan.jpeg", name: "SaiYan", role: "Researcher" },
          {
            image: "picture_jame.jpeg",
            name: "MasterJame",
            role: "Backend Subledger Developer",
          },
          { image: "picture_ohm.jpeg", name: "OSP22", role: "UX-UI Designer" },
          {
            image: "picture_ploy.jpeg",
            name: "Ploy",
            role: "Frontend Backoffice Developer",
          },
        ],
      };
    },
  };
  </script>
  
  <style scoped>
  .about-us {
    display: flex;
    justify-content: center;
    align-items: center;
    background: rgb(249, 251, 252);
  }
  .content {
    width: 80vw;
    padding: 1rem;
    margin-top: 5rem;
  }
  
  .topic {
    font-size: 3rem;
    color: rgb(23, 25, 63);
    font-weight: 500;
    text-align: center;
  }
  
  .profiles {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    gap: 3rem;
    margin-top: 5rem;
  }
  
  .primary_color {
    color: #11833a;
  }
  
  .secondary_color {
    color: #fea630;
  }
  
  .des_project {
    margin-top: 1rem;
    width: 100%;
    font-size: 1rem;
    text-align: center;
  }
  
  @media only screen and (max-width: 992px) {
    .profiles {
      grid-template-columns: repeat(2, 1fr);
    }
  
    .content {
      padding-top: 5rem;
    }
  }
  
  @media only screen and (max-width: 768px) {
    .circle {
      background-color: red;
    }
  }
  
  @media only screen and (max-width: 576px) {
    .profiles {
      gap: 1rem;
    }
  
    .content {
      width: 80vw;
      padding: 1rem;
      margin-top: 3rem;
    }
  
    .topic {
      font-size: 2rem;
      color: rgb(23, 25, 63);
      font-weight: 400;
      text-align: center;
    }

    @media only screen and (max-width:400px) {
      .topic{
        font-size: 1.1rem;
      }

      .des_project{
        font-size: .8rem;
      }

      .content{
        margin-top: 1.5rem;
        padding: 0;
      }

      .profiles {
      grid-template-columns: repeat(2, 1fr);
    }

    .about-us {
      padding-bottom: 2rem;
    }
    }
  }
  </style>
  