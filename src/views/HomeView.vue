<template>
  <div class="home">
    <!-- Header Section Begin -->
    <HeaderShayna />
    <!-- Header End -->
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HeaderShayna from "@/components/HeaderShayna.vue";

export default {
  name: "HomeView",
  components: {
    HeaderShayna,
  },
};
</script>
