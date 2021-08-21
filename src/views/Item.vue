<template>
  <div class="mx-auto max-w-6xl">
    <main>
      <div class="min-h-screen py-12 sm:pt-20">
        <div
          class="flex flex-col justify-center items-center md:flex-row md:items-start space-y-8 md:space-y-0 md:space-x-4 lg:space-x-8 max-w-6xl w-11/12 mx-auto"
        >
          <ItemImagePanel />
          <ItemDetailsPanel />
        </div>
      </div>
    </main>
  </div>
</template>

<script>
import ItemImagePanel from "@/components/ItemImagePanel.vue";
import ItemDetailsPanel from "@/components/ItemDetailsPanel.vue";

export default {
  name: "Home",
  props: ["id"],
  components: {
    ItemImagePanel,
    ItemDetailsPanel,
  },
};
</script>
