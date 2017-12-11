<template>
  <section class="container">
    <posts/>
  </section>
</template>

<script>
  import Posts from '~/components/Posts.vue'
  export default {
    components: {
      Posts
    }
  }
</script>



<style>
  .container {
    font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
    padding: 50px;
  }
</style>
