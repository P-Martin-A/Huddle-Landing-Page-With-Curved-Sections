<template>
  <section class="container">
    <Followers />
    <Grow />
    <Flowing />
    <Users />
    <Ready />
  </section>
</template>

<script>
  import Followers from '@/components/Followers'
  import Grow from '@/components/Grow'
  import Flowing from '@/components/Flowing'
  import Users from '@/components/Users'
  import Ready from '@/components/Ready'

  export default {
    name: 'Section',
    components: {
      Followers,
      Grow,
      Flowing,
      Users,
      Ready
    }
  }
</script>