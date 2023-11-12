<script>
import { defineComponent } from "vue";
import AppHeader from "@/components/Header.vue";
import AppFooter from "@/components/Footer.vue";
import AppLanguage from "@/components/Language.vue";

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

@media only screen and (max-width: 695px) {
  body {
    padding: 0px 1.5rem;
    background: #fafaf9;
  }
}
</style>
