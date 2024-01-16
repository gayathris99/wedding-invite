<template>
  <q-page class="flex flex-center">
    <hero-banner/>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'
import HeroBanner from 'src/components/HeroBanner.vue'

export default defineComponent({
  name: 'IndexPage',
  components: { HeroBanner }
})
</script>
