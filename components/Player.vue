<template>
  <div class="bassick-player">
    <vue-plyr ref="plyr" :options="options">
      <audio>
        <source src="audio.mp3" type="audio/mp3" />
        <source src="audio.ogg" type="audio/ogg" />
      </audio>
    </vue-plyr>
  </div>
</template>

<script>
// import Plyr from "plyr";

export default {
  data() {
    return {
      options: {
        controls: [
          "play-large",
          "play",
          "progress",
          "current-time",
          "mute",
          "volume"
        ]
      }
    };
  },
  computed: {
    player() {
      return this.$refs.plyr.player;
    }
  },
  mounted() {
    console.log(this.player);
  }
};
</script>

<style>
.bassick-player {
  position: fixed;
  bottom: 0;
  left: 0;
  right: 0;
}
</style>
