<template>
  <div class="post">
    <p>{{ id }}. {{ name }}</p>
    <p>{{ content }}</p>
  </div>
</template>

<script>
export default {
  name: 'Post',
  props: ['id', 'name', 'content']
}
</script>

<style>
  .post {
    padding: 1rem;
    border: 1px solid whitesmoke;
    margin: 1rem 0;
  }
</style>