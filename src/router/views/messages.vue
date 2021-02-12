<script>
import Layout from '@layouts/messages.vue'

export default {
  page: {
    title: 'Messages',
    meta: [{ name: 'description', content: 'The Messages page.' }],
  },
  components: { Layout }
}
</script>

<template>
  <Layout>
    Messages
  </Layout>
</template>

<style lang="scss" module>
@import '@design';
</style>
