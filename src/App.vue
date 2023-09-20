<template>
  <Loading v-show="loading"></Loading>
  <div v-show="!loading">
    <AppHeader />
    <router-view></router-view>
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue"
import AppFooter from "./components/AppFooter.vue"
import Loading from "./components/Loading.vue"

export default {
  name: 'App',
  data() {
    return {
      loading: true,
    }
  },
  mounted() {
    setTimeout(() => {
      this.loading = false
    }, 3000)
  },
  components: {
    AppHeader,
    AppFooter,
    Loading,
  }
}
</script>
