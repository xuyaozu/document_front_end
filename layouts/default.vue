<template>
  <div>
    <b-container fluid>
      <b-row fluid>
        <navbar />
      </b-row>
      <b-row>
        <Nuxt />
      </b-row>
    </b-container>
  </div>
</template>

<script>
import navbar from '../components/public/nav'
export default {
  components: {
    navbar
  }
}
</script>

<style lang="scss">
@import "@/assets/scss/main.scss";
</style>
