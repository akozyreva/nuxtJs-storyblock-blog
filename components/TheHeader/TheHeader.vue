<template lang="html">
  <header class="main-header">
    <div class="main-nav">
      <ul class="nav-links">
        <nuxt-link
          to="/"
          tag="li"><a>All Posts</a></nuxt-link>
        <nuxt-link
          to="about" 
          tag="li"><a>About</a></nuxt-link>
      </ul>
    </div>
  </header>
</template>

<script>

export default {
}
</script>

<style lang="stylus" scoped>
  .main-header
    position: fixed;
    top: 0
    left: 0
    width: 100%
    background: #022d30
</style>
