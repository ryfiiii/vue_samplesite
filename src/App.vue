<template>

  <AppHeader />

  <main>
    <router-view v-slot="{ Component }">
        <component :is="Component" />
    </router-view>
  </main>

  <AppFooter />
</template>

<script>
import AppHeader from "./components/AppHeader.vue"
import AppFooter from "./components/AppFooter.vue"

export default {
  name: 'App',
  components: {
    AppHeader,
    AppFooter,
  }
}
</script>
