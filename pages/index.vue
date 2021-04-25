<template>
  <section class="container">
    <div>
      <player />
      <hero />
      <about />
      <services />
      <hits />
      <contact />
      <foot />
    </div>
  </section>
</template>

<script>
import hero from "~/components/Hero.vue";
import about from "~/components/About.vue";
import services from "~/components/Services.vue";
import hits from "~/components/Hits.vue";
import contact from "~/components/Contact.vue";
import foot from "~/components/Footer.vue";
import player from "~/components/Player.vue";

export default {
  components: {
    hero,
    about,
    services,
    hits,
    contact,
    foot,
    player
  }
};
</script>
