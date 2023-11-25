<script>
import { defineComponent } from "vue";
import AppHeader from "@/components/Header.vue";
import AppFooter from "@/components/Footer.vue";
import AppLanguage from "@/components/Language.vue";
import Lenis from "@studio-freight/lenis";

const lenis = new Lenis({
  duration: 1.5,
});

lenis.on("scroll", (e) => {
  console.log(e);
});

function raf(time) {
  lenis.raf(time);
  requestAnimationFrame(raf);
}

requestAnimationFrame(raf);

export default defineComponent({
  name: "App",
  components: {
    AppHeader,
    AppFooter,
    AppLanguage,
  },
});
</script>

<template>
  <AppLanguage />
  <AppHeader />
  <router-view />
  <AppFooter />
</template>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Federo&family=Space+Grotesk:wght@300;400;500;600;700&display=swap");

#app {
  font-family: "Space Grotesk", Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

* {
  padding: 0px;
  margin: 0px;
  box-sizing: border-box;
}

body {
  width: 100vw;
  height: 100vh;
  padding: 0px 7.5rem;
  background: #fafafa;
  overflow-x: hidden;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}

html.lenis {
  height: auto;
}

.lenis.lenis-smooth {
  scroll-behavior: auto;
}

.lenis.lenis-smooth [data-lenis-prevent] {
  overscroll-behavior: contain;
}

.lenis.lenis-stopped {
  overflow: hidden;
}

.lenis.lenis-scrolling iframe {
  pointer-events: none;
}

@media only screen and (max-width: 695px) {
  body {
    padding: 0px 1.5rem;
    background: #fafaf9;
  }
}
</style>
