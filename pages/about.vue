<template>
  <div>
    <h1>About Us</h1>
    <p>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Fugit itaque officia ducimus repellendus! Porro quibusdam repellendus odit accusantium, accusamus quasi alias, possimus sint quisquam assumenda impedit, facilis nihil aut fugiat.
    </p>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: 'Posts | Nuxt Application',
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