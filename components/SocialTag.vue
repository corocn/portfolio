<template>
  <span class="tag is-large">
    <a v-bind:href="href">
      <span class="icon">
        <i v-bind:class="'fa fa-' + name"></i>
      </span>
    </a>
  </span>
</template>

<script>
  export default {
    props: ['name', 'href']
  }
</script>
