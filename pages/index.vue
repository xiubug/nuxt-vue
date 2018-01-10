<template>
  <div>
    <h1>Welcome!</h1>
    <h2>{{ title }}</h2>
    <nuxt-link to="/about">About page</nuxt-link>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        title: 'Nuxt - Index'
      }
    },
    head () {
      return {
        title: this.title,
        meta: [
          { hid: 'description', name: 'description', content: 'Index of Nuxt' }
        ]
      }
    }
  }
</script>
