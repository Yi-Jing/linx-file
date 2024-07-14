<script setup lang="ts">
import { computed } from 'vue'

const props = defineProps({
  type: {
    type: String,
    default: 'circle', // required: ['circle', 'underline']
  },
  at: {
    type: Number,
    default: 1,
  },
  width: {
    type: String,
    default: '200'
  },
  height: {
    type: String,
    default: '200'
  },
  top: {
    type: String,
    default: null
  },
  bottom: {
    type: String,
    default: null
  },
  left: {
    type: String,
    default: null
  },
  right: {
    type: String,
    default: null
  },
})

const styles = computed(() => {
  return {
    width: `${props.width}px`,
    height: `${props.height}px`,
    top: `${props.top}px`,
    bottom: `${props.bottom}px`,
    left: `${props.left}px`,
    right: `${props.right}px`,
  }
})
</script>

<template>
  <template v-if="props.type === 'circle'">
    <span 
      v-mark.circle.orange="props.at"
      class="absolute"
      :style="styles"
    ></span>
  </template>
  
  <template v-else>
    <span
      v-mark.underline.orange
      class="absolute"
      :style="styles"
    ></span>
  </template>
</template>
