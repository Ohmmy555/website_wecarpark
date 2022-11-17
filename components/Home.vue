<template>
  <div class="home">
    <div class="container">
      <div class="content">
        <div class="topic_name">
          <span class="primary_color">Easy Park</span
          ><span class="secondary_color"> Easy Pay</span>
        </div>
        <div class="des">
          A platform that lets parking space owners rent out their spaces to
          drivers looking for a place to park.
        </div>
        <div class="list-fun">
          <div class="list-item-1">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="25"
              height="25"
              fill="currentColor"
              class="bi bi-patch-check-fill primary_color icon"
              viewBox="0 0 16 16"
            >
              <path
                d="M10.067.87a2.89 2.89 0 0 0-4.134 0l-.622.638-.89-.011a2.89 2.89 0 0 0-2.924 2.924l.01.89-.636.622a2.89 2.89 0 0 0 0 4.134l.637.622-.011.89a2.89 2.89 0 0 0 2.924 2.924l.89-.01.622.636a2.89 2.89 0 0 0 4.134 0l.622-.637.89.011a2.89 2.89 0 0 0 2.924-2.924l-.01-.89.636-.622a2.89 2.89 0 0 0 0-4.134l-.637-.622.011-.89a2.89 2.89 0 0 0-2.924-2.924l-.89.01-.622-.636zm.287 5.984-3 3a.5.5 0 0 1-.708 0l-1.5-1.5a.5.5 0 1 1 .708-.708L7 8.793l2.646-2.647a.5.5 0 0 1 .708.708z"
              />
            </svg>
            <div class="des-list">Free registration</div>
          </div>
          <div class="list-item-1">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="25"
              height="25"
              fill="currentColor"
              class="bi bi-patch-check-fill primary_color icon"
              viewBox="0 0 16 16"
            >
              <path
                d="M10.067.87a2.89 2.89 0 0 0-4.134 0l-.622.638-.89-.011a2.89 2.89 0 0 0-2.924 2.924l.01.89-.636.622a2.89 2.89 0 0 0 0 4.134l.637.622-.011.89a2.89 2.89 0 0 0 2.924 2.924l.89-.01.622.636a2.89 2.89 0 0 0 4.134 0l.622-.637.89.011a2.89 2.89 0 0 0 2.924-2.924l-.01-.89.636-.622a2.89 2.89 0 0 0 0-4.134l-.637-.622.011-.89a2.89 2.89 0 0 0-2.924-2.924l-.89.01-.622-.636zm.287 5.984-3 3a.5.5 0 0 1-.708 0l-1.5-1.5a.5.5 0 1 1 .708-.708L7 8.793l2.646-2.647a.5.5 0 0 1 .708.708z"
              />
            </svg>
            <div class="des-list">Security</div>
          </div>
          <div class="list-item-1">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="25"
              height="25"
              fill="currentColor"
              class="bi bi-patch-check-fill primary_color icon"
              viewBox="0 0 16 16"
            >
              <path
                d="M10.067.87a2.89 2.89 0 0 0-4.134 0l-.622.638-.89-.011a2.89 2.89 0 0 0-2.924 2.924l.01.89-.636.622a2.89 2.89 0 0 0 0 4.134l.637.622-.011.89a2.89 2.89 0 0 0 2.924 2.924l.89-.01.622.636a2.89 2.89 0 0 0 4.134 0l.622-.637.89.011a2.89 2.89 0 0 0 2.924-2.924l-.01-.89.636-.622a2.89 2.89 0 0 0 0-4.134l-.637-.622.011-.89a2.89 2.89 0 0 0-2.924-2.924l-.89.01-.622-.636zm.287 5.984-3 3a.5.5 0 0 1-.708 0l-1.5-1.5a.5.5 0 1 1 .708-.708L7 8.793l2.646-2.647a.5.5 0 0 1 .708.708z"
              />
            </svg>
            <div class="des-list">Available on Android</div>
          </div>
        </div>
        
      </div>
    </div>

  </div>
</template>
  
  <script>
export default {};
</script>
  
  <style scoped>
@keyframes moveMent {
  0% {
    top: calc(50vh - 15rem);
  }
  25% {
    top: calc(50vh - 10rem);
  }
  50% {
    top: calc(50vh - 5rem);
  }
  75% {
    top: calc(50vh - 10rem);
  }
  100% {
    top: calc(50vh - 15rem);
  }
}

@keyframes wrap-animation {
  0% {
    background-color: #fea630;
  }
  25% {
    border: 0.3rem solid transparent;
    border-top: 0.3rem solid #fea630;
    border-right: 0.3rem solid #fea630;
    transform: rotate(0deg);
    background-color: transparent;
  }
  75% {
    transform: rotate(360deg);
  }
  100% {
    background-color: #fea630;
  }
}

@keyframes slideRight {
  from {
    margin-left: 0%;
  }
  to {
    margin-right: 13%;
    animation: shake 1s infinite;
  }
}

@keyframes slideLeft {
  from {
    margin-left: -40%;
  }
  to {
    margin-left: -30%;
    animation: shake 1s infinite;
  }
}

@keyframes shake {
  0% {
    margin-top: 0px;
    transition: all 0.3s ease-in-out;
  }
  10% {
    margin-top: 1px;
    transition: all 0.3s ease-in-out;
  }
  20% {
    margin-top: 2px;
    transition: all 0.3s ease-in-out;
  }
  30% {
    margin-top: 3px;
    transition: all 0.3s ease-in-out;
  }
  40% {
    margin-top: 4px;
    transition: all 0.3s ease-in-out;
  }
  50% {
    margin-top: 5px;
    transition: all 0.3s ease-in-out;
  }
  60% {
    margin-top: 4px;
    transition: all 0.3s ease-in-out;
  }
  70% {
    margin-top: 3px;
    transition: all 0.3s ease-in-out;
  }
  80% {
    margin-top: 2px;
    transition: all 0.3s ease-in-out;
  }
  90% {
    margin-top: 1px;
    transition: all 0.3s ease-in-out;
  }
  100% {
    margin-top: 0px;
    transition: all 0.3s ease-in-out;
  }
}

.home {
  min-height: 100vh;
  width: 1200px;
  margin: auto auto;
}

.container {
  display: flex;
  justify-content: center;
  align-content: center;
  min-height: 100vh;
}

.content {
  width: 100vw;
  margin: auto;
}

.img-content {
  width: 100vw;
}

.topic {
  font-size: 1.4rem;
  font-weight: 500;
}

.topic_name {
  font-size: 2.7rem;
  font-weight: 600;
}

.primary_color {
  color: #11833a;
}

.secondary_color {
  color: #fea630;
}

.des {
  margin-top: 0.5rem;
  width: 100%;
  font-size: 1rem;
  color: rgb(134, 134, 134);
}

.list-fun {
  display: flex;
}

.list-item-1 {
  font-size: 1rem;
  display: flex;
  justify-content: center;
  align-content: center;
  margin-top: 1rem;
  margin-right: 1rem;
}

.des-list {
  margin-left: 0.5rem;
}

.image-blog {
  display: flex;
  margin-top: 1rem;
}

.image-logo-download {
  height: 3rem;
}

.image-logo-download:nth-child(2) {
  margin-left: 2rem;
}

.image-logo {
  width: 100%;
}

.img-content {
  margin: auto;
}

.how-to-install {
  display: flex;
  margin-bottom: 2rem;
  justify-content: center;
}

.des-how {
  font-size: 0.8rem;
  color: #fea630;
  margin-left: 0.8rem;
}

.scroll-down {
  width: 32px;
  position: absolute;
  bottom: 40px;
  left: calc(50% - 16px);
}

@media only screen and (max-width: 768px) {
  .list-fun {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    place-items: start;
  }

  .image-logo-download {
    width: auto;
    height: 5rem;
    margin-bottom: 0.5rem;
  }
}
@media only screen and (max-width: 576px) {
  .list-fun {
    display: grid;
    grid-template-columns: repeat(1, 1fr);
    place-items: start;
    margin-top: 0.3rem;
  }
  .image-blog {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    place-items: start;
    column-gap: 1rem;
  }

  .image-logo-download {
    width: 10rem;
    height: auto;
    margin-bottom: 0.5rem;
  }

  .image-logo-download:nth-child(2) {
    margin-left: 0;
  }

  .topic {
    font-size: 1.3rem;
    font-weight: 600;
    text-align: center;
  }

  .topic_name {
    font-size: 2rem;
    font-weight: 600;
    text-align: center;
  }

  .des {
    margin-top: 0.3rem;
    width: 100%;
    font-size: 0.8rem;
    text-align: center;
  }

  .icon {
    width: 1rem;
  }

  .des-list {
    font-size: 0.8rem;
  }

  .list-item {
    justify-content: center;
    align-content: center;
    margin-top: 0.3rem;
    margin-right: 1rem;
  }

  .how-to-install {
    margin-top: 5rem;
    justify-content: center;
  }

  .img-content {
    width: 100vw;
    margin-top: 0;
  }

  .home {
    display: grid;
    grid-template-columns: 1fr;
    gap: 0rem;
    width: 100vw;
    margin-top: 0%;
    min-height: 50vh;
  }

  .content {
    width: 80%;
    margin-top: 5.5rem;
  }

  .container {
    display: grid;
    grid-template-columns: repeat(1, 1fr);
    min-height: 0;
  }
}
@media screen and (min-width: 360px) {
  .topic_name {
  font-size: 1.8rem;
  font-weight: 400;
}

.content {
  margin-top: 0;
}

}
</style>
  