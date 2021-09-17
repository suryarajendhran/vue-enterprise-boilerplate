<script>
import Layout from '@layouts/main.vue'

export default {
  page: {
    title: 'Dashboard',
    meta: [{ name: 'description', content: 'The Dashboard page.' }],
  },
  components: { Layout },
}
</script>

<template>
  <Layout>
    Dashboard
  </Layout>
</template>

<style lang="scss" module>
@import '@design';
</style>
