<template>
  <div class="bassick-services-wrapper">
    <div class="bassick-services-title"><span>Services</span></div>
    <div class="bassick-services">
      <div class="bassick-service">
        <img src="~assets/services/service-composing.png" alt="" />
        <div>Composing</div>
      </div>
      <div class="bassick-service">
        <img src="~assets/services/service-mixing.png" alt="" />
        <div>Mixing</div>
      </div>
      <div class="bassick-service">
        <img src="~assets/services/service-production.png" alt="" />
        <div>Production</div>
      </div>
      <div class="bassick-service">
        <img src="~assets/services/service-recording.png" alt="" />
        <div>Recording</div>
      </div>
    </div>
  </div>
</template>

<style>
.bassick-services-wrapper {
  padding: 100px;
  /* display: flex; */
  /* flex-direction: column; */
  /* align-items: center; */
  background-color: rgb(18, 18, 18);
  color: white;
}
.bassick-services-title {
  display: flex;
  justify-content: center;
}
.bassick-services {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}
.bassick-services-wrapper > div > span {
  font-size: 36px;
  font-weight: 200;
}
.bassick-service {
  margin: 100px;
  /* color: white; */
  display: flex;
  flex-direction: column;
  align-items: center;
}
.bassick-service div {
  font-size: 20px;
}
</style>
