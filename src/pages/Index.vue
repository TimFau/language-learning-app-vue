<template>
  <q-page class="flex flex-center">
    <flash-card></flash-card>
  </q-page>
</template>

<script>
import FlashCard from '../components/FlashCard.vue'
export default {
  name: 'PageIndex',
  components: {
    'flash-card': FlashCard
  }
}
</script>
