<template>
  <section class="post-list">
    <PostPreview
      id="1"
      :is-admin="isAdmin"
      thumbnail="https://www.homage.sg/wp-content/uploads/2018/09/47724337_l-1080x675.jpg"
      title="Hello there"
      previewText="This is my first post!"
    />
    <PostPreview
      id="2"
      :is-admin="isAdmin"
      thumbnail="https://www.homage.sg/wp-content/uploads/2018/09/47724337_l-1080x675.jpg"
      title="Hello there for the second time"
      previewText="This is my first post!"
    />
    <PostPreview
      id="3"
      :is-admin="isAdmin"
      thumbnail="https://www.homage.sg/wp-content/uploads/2018/09/47724337_l-1080x675.jpg"
      title="Hello there - Hi!"
      previewText="This is my first post!"
    />
  </section>
</template>

<script>
  import PostPreview from '@/components/Posts/PostPreview';

  export default {
    name: 'PostList',
    components: {
      PostPreview
    },
    props:{
      isAdmin:{
        type: Boolean,
        default: false
      }
    }
  }
</script>

<style scoped lang="scss">

  .post-list {
    display: flex;
    padding: 20px;
    box-sizing: border-box;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
  }

</style>
