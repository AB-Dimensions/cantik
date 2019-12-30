<template>
  <div class="wrapper">
    <globalHeader />
    <main class="main">
      <section class="intro-section">
      </section>
    </main>
  </div>
</template>

<script>
import globalHeader from '@/components/header'

export default {
  layout: 'default',
  components: {
    globalHeader
  }
}
</script>

<style>
.wrapper {
  position: relative;
  overflow: hidden;
}
.main {
  padding-top: 72px;
}

/* intro section */
.intro-section {
  text-align: center;
  padding: 48px 4px 0;
  overflow: hidden;
}
</style>
