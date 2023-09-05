<template>

  <AppHeader />

  <main>
    <router-view></router-view>
  </main>

  <AppFooter />
</template>

<script>
import AppHeader from "./components/AppHeader.vue"
import AppFooter from "./components/AppFooter.vue"
import Home from "./components/pages/Home.vue"
import About from "./components/pages/About.vue"
import Contact from "./components/pages/Contact.vue"

export default {
  name: 'App',
  components: {
    AppHeader,
    AppFooter,
    Home,
    About,
    Contact,
  }
}
</script>
