<template>
  <tiny-slider v-model="value2" :unit="unit" :show-input="true"></tiny-slider>
</template>

<script>
import { Slider } from '@opentiny/vue'

export default {
  components: {
    TinySlider: Slider
  },
  data() {
    return {
      value2: 40,
      unit: '%'
    }
  }
}
</script>
