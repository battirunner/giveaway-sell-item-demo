<template>
  <div class="mx-auto max-w-6xl">
    <Header />
    <ItemsGrid />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import ItemsGrid from "@/components/ItemsGrid.vue";

export default {
  name: "Home",
  components: {
    Header,
    ItemsGrid,
  },
};
</script>
