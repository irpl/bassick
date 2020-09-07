<template>
  <section class="container">
    <div>
      <hero />
      <about />
      <services />
      <hits />
      <contact />
      <foot />
      <!-- <logo /> -->
      <!-- <h1 class="title">
        bassick
      </h1>
      <h2 class="subtitle">
        BassickRecJA
      </h2>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          class="button--green"
        >Documentation</a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="button--grey"
        >GitHub</a>
      </div> -->
    </div>
  </section>
</template>

<script>
// import Logo from '~/components/Logo.vue'
import hero from "~/components/Hero.vue";
import about from "~/components/About.vue";
import services from "~/components/Services.vue";
import hits from "~/components/Hits.vue";
import contact from "~/components/Contact.vue";
import foot from "~/components/Footer.vue";

export default {
  components: {
    // Logo,
    hero,
    about,
    services,
    hits,
    contact,
    foot
  }
};
</script>

<style>
/* .container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
} */
</style>
