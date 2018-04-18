<template lang="pug">
span.social-tag
  a(v-bind:href='href')
    span.icon.is-size-1
      i(v-bind:class="'fa fa-' + name")
</template>

<script>
  export default {
    props: ['name', 'href']
  }
</script>

<style scoped>
.social-tag {
  margin: 20px;
}
</style>