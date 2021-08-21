<template>
  <div
    class="py-12 max-w-6xl mx-auto grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-x-4 gap-y-8"
  >
    <Item v-for="item in itemsData" :key="item.id" :item="item" />
  </div>
</template>
<script>
import Item from "@/components/Item.vue";

export default {
  name: "ItemsGrid",
  components: {
    Item,
  },
  data() {
    return {
      itemsData: [],
    };
  },
  created() {
    this.itemsData = [
      {
        id: 1,
        title: "dfsd",
        img: "https://source.unsplash.com/user/erondu/400x400",
        price: 100,
      },
      {
        id: 2,
        title: "dfsd",
        img: "https://source.unsplash.com/user/erondu/400x400",
        price: 300,
      },
      {
        id: 3,
        title: "dfsd",
        img: "https://source.unsplash.com/user/erondu/400x400",
        price: 150,
      },
      {
        id: 4,
        title: "dfsd",
        img: "https://source.unsplash.com/user/erondu/400x400",
        price: 200,
      },
      {
        id: 5,
        title: "dfsd",
        img: "https://source.unsplash.com/user/erondu/400x400",
        price: 100,
      },
    ];
  },
};
</script>
