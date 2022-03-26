<template>
  <div>
    <carousel-images/>
    <prices/>
  </div>
</template>

<script>
import CarouselImages from '@/components/CarouselImages.vue'
import Prices from '@/components/Prices.vue'

export default {
  name: 'Home',
  components: {
    CarouselImages,
    Prices
  }
}
</script>
