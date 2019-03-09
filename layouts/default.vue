<template>
  <div>
    <TheHeader/>
    <main class="main-content">
      <nuxt />
    </main>
  </div>
</template>

<script type="text/javascript">
import TheHeader from '@/components/TheHeader/TheHeader'
export default {
  components: {
    TheHeader
  }
}
</script>

<style lang="stylus">
  *
    box-sizing: border-box;
body
    font-family: ZCOOL QingKe HuangYou, sans-serif;

.main-content
    margin-top: 4.5rem
</style>
