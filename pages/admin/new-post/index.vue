<template>
  <div class="admin-new-post-page">
    <section class="new-post-form">
      <AdminPostForm/>
    </section>
  </div>
</template>

<script>

  import AdminPostForm from '../../../components/admin/AdminPostForm';

  export default {
    name: 'index',
    components: {AdminPostForm}
  }
</script>

<style scoped>

</style>
