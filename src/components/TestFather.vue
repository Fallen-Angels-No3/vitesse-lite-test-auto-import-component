<script lang="ts" setup>
onMounted(() => {
  console.warn('onMounted')
})
</script>

<template>
  <div>
    <h1 mt-10 text-2xl>
      test father
    </h1>
    <slot name="header" />
    <slot />
  </div>
</template>
