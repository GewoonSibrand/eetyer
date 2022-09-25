<template>
  <div>
    <VHeader />
    <Banner class="mb-12"/>
    <section class="container mx-auto flex space-x-8">
      <VFeatureBlock />
      <VFeatureBlock />
      <VFeatureBlock />
    </section>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import VHeader from '~/components/VHeader.vue'
import VFeatureBlock from '~/components/VFeatureBlock.vue'
import Banner from '~/components/Banner.vue'

export default Vue.extend({
  name: 'IndexPage',
  components: { VHeader, VFeatureBlock, Banner },
})
</script>
