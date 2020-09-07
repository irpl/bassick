<template>
  <div class="bassick-section">
    <div class="bassick-about-pic">
      <!-- <img src="https://picsum.photos/500/600" alt="" /> -->
      <img src="~assets/bassick-stefan-bw.jpg" alt="" />
    </div>
    <div class="bassick-about-body">
      <h1>Some Title</h1>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis aliquet at
        massa quis tempus. Cras maximus elementum lacinia. Suspendisse semper
        leo purus, dapibus iaculis eros porta eget. Maecenas accumsan nunc
        sapien, ut pulvinar mauris pretium non. Curabitur suscipit nisl a orci
        molestie auctor. Duis dignissim leo id nulla tempus pulvinar. Lorem
        ipsum dolor sit amet, consectetur adipiscing elit. Donec scelerisque
        ante at convallis facilisis. Quisque massa purus, ultrices non mauris
        vel, rutrum vestibulum leo.
      </p>
    </div>
  </div>
</template>
<script>
export default {};
</script>

<style>
.bassick-section {
  display: flex;
  flex-flow: row wrap;
  padding: 5rem 30px;
  color: white;
  /* width: 100%; */
  justify-content: space-evenly;
  /* align-content: center; */
  align-items: center;
  position: relative;
  background: linear-gradient(rgba(0, 0, 0, 0.9), rgba(0, 0, 0, 0.9)),
    url("~assets/studio.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
/* .bassick-section::after {
  content: "";
  background: url("https://images.squarespace-cdn.com/content/v1/523763a4e4b05227e95792ab/1569595419692-ZWJTEUQ9NHJMNT8O2A36/ke17ZwdGBToddI8pDm48kLkXF2pIyv_F2eUT9F60jBl7gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z4YTzHvnKhyp6Da-NYroOW3ZGjoBKy3azqku80C789l0iyqMbMesKd95J-X4EagrgU9L3Sa3U8cogeb0tjXbfawd0urKshkc5MgdBeJmALQKw/DSC_0275.jpg?format=1000w");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  opacity: 0.1;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  position: absolute;
  z-index: -1;
} */
.bassick-about-pic {
  /* background-color: #2b3618; */
  /* background-color: #0a1e19; */
  background-color: #101816;
  padding: 30px;
  /* border: 20px solid darkgreen; */
  /* margin: 20px; */
}

.bassick-about-pic img {
  display: block;
  width: 100%;
}
.bassick-about-body {
  /* margin: auto; */
  font-size: 1.5rem;
  width: 40%;
  vertical-align: middle;
  /* justify-content: space-around; */
  /* background-color: pink; */
  /* padding: 0 40px; */
  /* min-height: 100vh; */
  /* display: flex; */
  /* align-items: center; */
  /* text-align: center; */
}
@media only screen and (max-width: 600px) {
  /* .bassick-about-pic {
    display: block;
    width: 90%;
  } */
  .bassick-about-body {
    margin-top: 20px;
    width: 100%;
    font-size: 1.25rem;
  }
}
</style>
