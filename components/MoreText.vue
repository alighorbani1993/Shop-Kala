<template>
  <div class="expandable-text pt-1" :style="{ 'height': `${height}px` }">
    <div class="expandable-text_text fa-num">
      <slot />
    </div>
    <div class="expandable-text-expand-btn justify-content-start text-sm">
      <span class="show-more active">
        مشاهده بیشتر <i class="ri-arrow-down-s-line ms-2"></i></span
      ><span class="show-less d-none"> بستن <i class="ri-arrow-up-s-line ms-2"></i></span>
    </div>
  </div>
</template>

<script setup>
const props = defineProps({
  height: {
    default: 100,
    // type: Number,
  },
});
</script>

<style lang="scss" scoped></style>
