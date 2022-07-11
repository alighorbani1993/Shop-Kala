<template>
  <div class="page-wrapper">
    <!-- start of page-header -->
    <HeadersTheHeader></HeadersTheHeader>
    <HeadersResponsiveHeader></HeadersResponsiveHeader>
    <!-- end of page-header -->
    <main class="page-content">
      <div class="container">
        <slot />
      </div>
    </main>
    <TheFooter></TheFooter>
  </div>
</template>

<script setup lang="ts">
// import TheHeader from '~~/components/Headers/TheHeader.vue';
// import ResponsiveHeader from '~~/components/Headers/ResponsiveHeader.vue';
useHead({
  link: [
    { rel: "stylesheet", href: "/css/dependencies.css" },
    { rel: "stylesheet", href: "/css/theme.css" },
    { rel: "stylesheet", href: "/css/custom.css" },
  ],
  script: [
    { src: "/js/dependencies/jquery-3.6.0.min.js" },
    { src: "/js/dependencies/bootstrap.bundle.min.js" },
    { src: "/js/dependencies/bootstrap-slider.min.js" },
    { src: "/js/dependencies/jquery.countdown.min.js" },
    { src: "/js/dependencies/jquery.simple.timer.min.js" },
    { src: "/js/dependencies/iziToast.min.js" },
    { src: "/js/dependencies/fancybox.umd.js" },
    { src: "/js/dependencies/nouislider.min.js" },
    { src: "/js/dependencies/wNumb.js" },
    { src: "/js/dependencies/remodal.min.js" },
    { src: "/js/dependencies/select2.min.js" },
    { src: "/js/dependencies/simplebar.min.js" },
    { src: "/js/dependencies/swiper-bundle.min.js" },
    { src: "/js/dependencies/zoomsl.min.js" },
    { src: "/js/theme.js" },
    { src: "/js/custom.js" },
  ],
});
</script>

<style lang="scss" scoped></style>
