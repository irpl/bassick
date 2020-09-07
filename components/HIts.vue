<template>
  <div class="bassick-hits-wrapper">
    <span>Hits</span>
    <div class="bassick-hits">
      <div class="bassick-hit">
        <div class="bassick-hit-info">
          <img src="~assets/hits/hit-1.jpg" alt="" />
          <div class="bassick-hit-info-title">Bro Bro (2019)</div>
          <div>Ding Dong</div>
          <div>Some Riddim</div>
          <div class="bassick-hit-info-links">
            <div class="bassick-hit-info-link bassick-hit-info-link-spotify">
              <i class="fab fa-spotify"></i> spotify
            </div>
            <div class="bassick-hit-info-link bassick-hit-info-link-youtube">
              <i class="fab fa-youtube"></i> youtube
            </div>
            <div class="bassick-hit-info-link bassick-hit-info-link-soundcloud">
              <i class="fab fa-soundcloud"></i> soundcloud
            </div>
          </div>
        </div>
      </div>
      <div class="bassick-hit">
        <div class="bassick-hit-info">
          <img src="~assets/hits/hit-1.jpg" alt="" />
          <div class="bassick-hit-info-title">Bro Bro (2019)</div>
          <div>Ding Dong</div>
          <div>Some Riddim</div>
          <div class="bassick-hit-info-links">
            <div class="bassick-hit-info-link bassick-hit-info-link-spotify">
              <i class="fab fa-spotify"></i> spotify
            </div>
            <div class="bassick-hit-info-link bassick-hit-info-link-youtube">
              <i class="fab fa-youtube"></i> youtube
            </div>
            <div class="bassick-hit-info-link bassick-hit-info-link-soundcloud">
              <i class="fab fa-soundcloud"></i> soundcloud
            </div>
          </div>
        </div>
      </div>
      <div class="bassick-hit">
        <div class="bassick-hit-info">
          <img src="~assets/hits/hit-1.jpg" alt="" />
          <div class="bassick-hit-info-title">Bro Bro (2019)</div>
          <div>Ding Dong</div>
          <div>Some Riddim</div>
          <div class="bassick-hit-info-links">
            <div class="bassick-hit-info-link bassick-hit-info-link-spotify">
              <i class="fab fa-spotify"></i> spotify
            </div>
            <div class="bassick-hit-info-link bassick-hit-info-link-youtube">
              <i class="fab fa-youtube"></i> youtube
            </div>
            <div class="bassick-hit-info-link bassick-hit-info-link-soundcloud">
              <i class="fab fa-soundcloud"></i> soundcloud
            </div>
          </div>
        </div>
      </div>
      <div class="bassick-hit">
        <div class="bassick-hit-info">
          <img src="~assets/hits/hit-1.jpg" alt="" />
          <div class="bassick-hit-info-title">Bro Bro (2019)</div>
          <div>Ding Dong</div>
          <div>Some Riddim</div>
          <div class="bassick-hit-info-links">
            <div class="bassick-hit-info-link bassick-hit-info-link-spotify">
              <i class="fab fa-spotify"></i> spotify
            </div>
            <div class="bassick-hit-info-link bassick-hit-info-link-youtube">
              <i class="fab fa-youtube"></i> youtube
            </div>
            <div class="bassick-hit-info-link bassick-hit-info-link-soundcloud">
              <i class="fab fa-soundcloud"></i> soundcloud
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  head() {
    return {
      script: [
        {
          src: "https://kit.fontawesome.com/f0f1d79673.js",
          crossorigin: "anonymous"
        }
      ]
    };
  }
};
</script>
<style>
.bassick-hits-wrapper {
  padding: 100px;
  display: flex;
  flex-direction: column;
  align-items: center;
  color: white;
}
.bassick-hits-wrapper > span {
  font-size: 36px;
  font-weight: 200;
}
.bassick-hits {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}
.bassick-hit {
  margin: 40px;
  width: 300px;
}
.bassick-hit img {
  width: 100%;
  /* margin-bottom: 10px; */
}
.bassick-hit-info {
  border: 1px solid rgba(255, 255, 255, 0.4);
  padding: 20px;
  color: #7b7b7b;
}
.bassick-hit-info-title {
  font-weight: 200;
  font-size: 36px;
  color: white;
  margin: 10px 0;
}
.bassick-hit-info-links {
  /* display: flex; */
  /* flex-wrap: wrap; */
  /* justify-content: space-evenly; */
  margin-top: 20px;
}
.bassick-hit-info-link {
  cursor: pointer;
  border: 1px solid rgba(255, 255, 255, 0.4);
  border-radius: 4px;
  padding: 10px;
  margin: 10px 15px;
  font-weight: 700;
  transition: background-color 0.5s ease 0s;
  transition: color 0.5s ease 0s;
}
.bassick-hit-info-link-soundcloud:hover {
  background-color: #3b1000;
  color: white;
}
.bassick-hit-info-link-youtube:hover {
  background-color: #270000;
  color: white;
}
.bassick-hit-info-link-spotify:hover {
  /* background-color: green; */
  background-color: #002700;
  color: white;
}
</style>
