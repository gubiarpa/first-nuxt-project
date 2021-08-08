<template>
  <h1>Welcome to out first Nuxt App</h1>
</template>

<script>
export default {
  head() {
    return {
      title: 'Application Nuxt Posts | Home',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Website about posts'
        }
      ],
      htmlAttrs: {
        lang: 'en'
      }
    }
  }
}
</script>