<template>
  <section class="container">
<!--    <Header/>-->
    <nuxt-link to="/users" class="button--grey">Users</nuxt-link>
    <button @click="goToProductsPage">Products</button>
  </section>
</template>

<script>
  // import Header from '~/components/Header.vue'

  export default {
    // components: {
    //   Header
    // },
    methods: {
      goToProductsPage() {
        this.$router.push('/products')
      }
    }
  }
</script>

<style>

</style>
