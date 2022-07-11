<template>
  <div>
    <div v-if="slots.default" class="form-element-row with-btn mt-5 text-start">
      <input type="text" class="form-control" v-bind="$attrs" v-model="modelValue" />

      <!-- <input
        type="text"
        class="form-control"
        v-bind="$attrs"
        v-model="modelValue"
        @input="update"
      /> -->

      <slot />
    </div>

    <input
      v-else
      v-bind="$attrs"
      type="text"
      class="form-control text-right"
      placeholder="آدرس ایمیل خود را وارد کنید"
      v-model="modelValue"
    />

    <!-- <input
      v-else
      v-bind="$attrs"
      type="text"
      class="form-control text-right"
      placeholder="آدرس ایمیل خود را وارد کنید"
      v-model="modelValue"
      @input="update"
    /> -->
  </div>
</template>

<script>
export default {
  inheritAttrs: false,
};
</script>

<script setup>
const slots = useSlots();
// console.log(slots);
// const emits = defineEmits(["update:modelValue"]);
const props = defineProps({
  modelValue: {
    type: String,
    default: "",
  },
});

// function update(e) {
//   emits("update:modelValue", e.target.value);
// }
</script>

<style lang="scss" scoped></style>
