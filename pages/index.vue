<template>
  <div class="home-page">
    <section class="intro">
      <h1>Get the latest tech news!</h1>
    </section>
    <section class="featured-posts">
      <nuxt-link :to="'/posts/+1'">
        <article class="post-review">
          <div class="post-thumbnail"></div>
          <div class="post-content">
            <h1>Post title</h1>
            <p>Preview text</p>
          </div>
        </article>
      </nuxt-link>
    </section>
  </div>
</template>

<script>

  export default {
    components: {}
  }
</script>

<style>

</style>
