<template>
  <footer class="footer container">   
    <div class="wavy"></div>
    <Newsletter />
    <Contact />
  </footer>
</template>

<script>
  import Newsletter from '@/components/Newsletter'
  import Contact from '@/components/Contact'

  export default {
    name: 'Footer',
    components: {
      Newsletter,
      Contact
    }
  }
</script>