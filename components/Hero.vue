<template>
  <div class="hero-image">
    <div class="hero-text">
      <p>Some top text</p>
      <h1>BassickRec JA</h1>
      <p>Something about music</p>
      <p>Some other text</p>
    </div>
    <!-- <div>
      <audio id="player" controls>
        <source src="http://www.robbynkirmsse.com/Resources/5-%20RememberROBBYN.mp3" type="audio/mp3" />
        <source src="/path/to/audio.ogg" type="audio/ogg" />
      </audio>
    </div> -->
  </div>
</template>

<script>
// import VuePlyr from 'vue-plyr'
import Plyr from "plyr";
// import 'plyr/dist/plyr.css'
export default {
  data() {
    return {
      player: null
    };
  }

  // mounted() {
  // this.player = new Plyr("#player");
  // }
};
</script>

<style>
body,
html {
  margin: 0;
}

.hero-image {
  background-image: linear-gradient(rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.8)),
    url("~assets/synth.jpg");
  /* background: url("https://www.adorama.com/alc/wp-content/uploads/2017/08/shutterstock_630161714-825x465.jpg"); */
  height: 100vh;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  /* position: absolute; */
  /* top: 0; */
  z-index: -1;
  display: flex;
  align-items: center;
  align-content: center;
}
/* .hero-image::after {
  opacity: 0.1;
} */

.hero-text {
  /* text-align: center;
  position: absolute;
  top: 40%;
  left: 25%;
  transform: translate(-50%, -50%);*/
  color: white;

  display: flex;
  /* height: 100vh; */
  flex-direction: column;
  /* align-content: center; */
  align-items: center;
  margin: 0 15%;
  margin-top: -100px;
}
.hero-text h1 {
  font-size: 5rem;
}
.hero-text p {
  font-size: 1.8rem;
}
@media only screen and (max-width: 600px) {
  .hero-text {
    margin: auto;
  }
  .hero-text h1 {
    font-size: 3.5rem;
  }
}
</style>
