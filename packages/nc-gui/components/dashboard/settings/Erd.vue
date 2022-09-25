<script setup lang="ts">
interface Props {
  baseId: string
}

const props = defineProps<Props>()
</script>

<template>
  <div class="w-full h-full !py-0 !px-2" style="height: 70vh">
    <ErdView :base-id="props.baseId" />
  </div>
</template>
