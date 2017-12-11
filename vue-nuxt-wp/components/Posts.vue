<template>
  <section>

    <article  v-for="post in posts">
      <nuxt-link :to="`/post/${post.code.hex}`" >
        {{ post.color }}
      </nuxt-link>
    </article>

  </section>
</template>

<script>
  import posts from '../posts.json'

  export default {
    name: 'posts',
    data () {
      return { posts }
    }
  }
</script>
