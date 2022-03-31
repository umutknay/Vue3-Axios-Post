<template>
  <div class="divcontainer">
    <div class="row">
       <div class="col-md-12">
          <PostCreate></PostCreate>
       </div>
    </div> 
  </div>
</template>

<script>
import PostCreate from './components/PostCreate.vue'

export default {
  name: 'App',
  components: {
    PostCreate
  }
}
</script>

<style>
</style>
