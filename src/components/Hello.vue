<template lang="pug">
.eg-slideshow
    slide
      h1 Hi there !
      p I am the first slide !
    slide
      h1 Hi there !
      p I am the second slide !
</template>

<script>
import eagle from 'eagle.js'

export default {
  mixins: [ eagle.slideshow ],
  infos: {
    title: 'Your First Slideshow',
    description: 'A boilerplate to get you started'
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
