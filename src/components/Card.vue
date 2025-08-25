<script setup>
import { defineProps } from 'vue';
defineProps({
    bg:String,
    default: 'bg-gray-100'
})
</script>

<template>
  <div :class="`${type} p-6 rounded-lg shadow-md `">
    <slot></slot>
  </div>
</template>
