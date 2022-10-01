<script setup lang="ts">
const props = defineProps<{
  baseId: string
}>()
</script>

<template>
  <div class="w-full h-full !py-0 !px-2" style="height: 70vh">
    <ErdView :base-id="props.baseId" />
  </div>
</template>
