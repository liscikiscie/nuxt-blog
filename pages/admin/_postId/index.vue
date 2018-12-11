<template>
  <div class="admin-post-page">
    <section class="update-form">
      <AdminPostForm :post="loadedPost"/>
    </section>
  </div>
</template>

<script>
  import AdminPostForm from '@/components/admin/AdminPostForm';

  export default {
    name: 'index',
    components: {
      AdminPostForm
    },
    data(){
      return{
        loadedPost: {
          author: 'Qba',
          title: 'My post',
          content: 'Cool content',
          thumbnailLink: 'https://www.homage.sg/wp-content/uploads/2018/09/47724337_l-1080x675.jpg'
        }
      }
    }
  }
</script>

<style scoped>

</style>
