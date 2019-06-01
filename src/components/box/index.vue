<template>
  <div :style="{margin:gap,height:height}">
    <slot></slot>
  </div>
</template>

<script>
  export default {
    name: 'box',
    props: {
      gap: String,
      height: String,
    }
  }
</script>
