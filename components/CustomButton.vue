<template>
  <button
    :class="[
      { btn: true, 'btn-block': block, 'fw-bold': bold },
      outline ? `btn-outline-${color}` : `btn-${color}`,
    ]"
  >
    <slot></slot>
  </button>
</template>

<script setup>
const props = defineProps({
  block: {
    type: Boolean,
    default: false,
  },
  color: {
    type: String,
    default: "primary",
  },
  outline: {
    type: Boolean,
    default: false,
  },
  bold: {
    type: Boolean,
    default: false,
  },
});
</script>

<style lang="scss" scoped></style>
