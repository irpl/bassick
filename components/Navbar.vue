<template>
  <header class="navbar" ref="navbar">
    <div class="content-wrapper">
      <nuxt-link to="/">
        <div class="branding">
          <div class="pic">
            <img src="~assets/logo-white.png" alt="" />
          </div>
          <div>
            <div class="nav-title">Bassick Records JA.</div>
            <div class="nav-subtitle">Tag line</div>
          </div>
        </div>
      </nuxt-link>
      <!-- {{currentRoute}} -->
      <div class="navs">
        <div class="nav-btn" :class="{ active: currentRoute === '' }">Home</div>
        <div class="nav-btn" :class="{ active: currentRoute === 'boop' }">
          About
        </div>
        <div class="nav-btn" :class="{ active: currentRoute === 'bap' }">
          Services
        </div>
        <div class="nav-btn" :class="{ active: currentRoute === 'bap' }">
          Hits
        </div>
        <div class="nav-btn" :class="{ active: currentRoute === 'bap' }">
          Contact
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  computed: {
    currentRoute() {
      return this.$route.name;
    }
  },
  mounted() {
    window.addEventListener("scroll", this.handleScroll);
  },
  beforeDestroy() {
    window.removeEventListener("scroll", this.handleScroll);
  },
  methods: {
    handleScroll(event) {
      if (event.target.documentElement.scrollTop > 80) {
        this.$refs["navbar"].classList.add("opaque");
      } else {
        this.$refs["navbar"].classList.remove("opaque");
      }
    }
  }
};
</script>

<style>
a {
  text-decoration: none;
}
.navbar {
  padding: 1rem 0;
  width: 100%;
  margin: 0 auto;
  transition: background-color 0.5s ease 0s;
  position: fixed;
  z-index: 1;
  /* top: 0; */
  /* height: 50px; */
}
.content-wrapper {
  width: 80%;
  margin: 0 auto;
  color: white;
}
.branding {
  color: white;
  display: flex;
}
.branding .pic img {
  height: 50px;
  /* -webkit-filter: drop-shadow(0px 0px 6px rgba(255, 255, 255, 0.7)); */
  /* filter: drop-shadow(0px 0px 6px rgba(255, 255, 255, 0.7)); */
}
.navs {
  display: flex;
  justify-content: space-between;
  align-items: center;
  color: white;
}
.nav-btn {
  height: 80%;
  margin-left: 1.5rem;
  padding: 0.8rem 1rem;
  text-align: center;
}
@media only screen and (max-width: 600px) {
  .nav-btn {
    margin-left: unset;
  }
}
/* .nav-btn:last-of-type */
.active {
  background-color: black;
  border-radius: 5px;
  color: white;
  padding: 1em;
}
.nav-title {
  display: block;
  font-weight: 300;
  font-size: 1.2rem;
  /* color: white; */
  letter-spacing: 1px;
}

.nav-subtitle {
  font-weight: 300;
  font-size: 0.9rem;
  /* color: #526488; */
  word-spacing: 5px;
  /* padding-bottom: 15px; */
}
.content-wrapper {
  margin: 0 auto;
  /* max-width: 90vw; */
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.opaque {
  /* background-color: #101816f7; */
  background-color: rgba(16, 24, 22, 0.97);
}
@media only screen and (max-width: 600px) {
  .content-wrapper {
    display: block;
  }
}
</style>
