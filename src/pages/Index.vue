<template>
  <q-page class="flex flex-center">
    <img
      alt="Quasar logo"
      src="~assets/quasar-logo-full.svg"
    >
    <thong-tin/>
  </q-page>
</template>

<script>
import ThongTin from './components/ThongTin.vue'
export default {
  components: { ThongTin },
  name: 'PageIndex'
}
</script>
