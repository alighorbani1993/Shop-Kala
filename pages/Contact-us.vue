<template>
  <div>
    <h1>hi baby</h1>
    <more-text height="50">
      لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ، و با استفاده از طراحان
      گرافیک است، چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است، و
      برای شرایط فعلی تکنولوژی مورد نیاز، و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی
      می باشد،
    </more-text>

    <!-- <CustomButton block color="danger" outline>سلام</CustomButton> -->

    <!-- <Input type="number" placeholder="سلام" class="text-danger" v-model="text">
      <button class="btn btn-primary">ثبت</button>
    </Input> -->
    {{ text }}
  </div>
</template>

<script setup>
const text = ref("");
</script>

<style lang="scss" scoped></style>
