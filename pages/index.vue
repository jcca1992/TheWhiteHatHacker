<template>
  <nuxt-content :document="doc" />
</template>

<script>
export default {
  name: 'IndexPage',
  async asyncData({ $content }) {
    const doc = await $content('Getting started INFOSEC').fetch()

    return { doc }
  },
}
</script>
