<template>
  <div class="product">
    <HeaderShayna />
    <p>ini adalah halaman product</p>
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HeaderShayna from "@/components/HeaderShayna.vue";
import FooterShayna from "@/components/FooterShayna.vue";

export default {
  name: "ProductView",
  components: {
    HeaderShayna,
    FooterShayna,
  },
};
</script>
