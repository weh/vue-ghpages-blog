<template>
  <footer class="footer">
    Copyright © {{ thisYear }} | Powered by <a href="https://github.com/weh/vue-ghpages-blog" target="_blank">vue-ghpages-blog</a>
  </footer>
</template>

<script>
  export default {
    data () {
      return {
        thisYear: new Date().getFullYear()
      }
    }
  }
</script>
