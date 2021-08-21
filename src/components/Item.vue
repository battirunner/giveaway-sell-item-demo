<template>
  <a
    class="h-120 w-72 rounded shadow-lg mx-auto border border-palette-lighter"
    :href="'/item/' + item.id"
  >
    <!-- <h1>{{ item.title }}</h1> -->
    <div class="h-72 border-b-2 border-palette-lighter relative">
      <div class="block absolute inset-0 m-0">
        <img
          class="transform duration-500 ease-in-out hover:scale-110"
          :src="item.img"
          alt=""
        />
      </div>
    </div>
    <div class="h-48 relative">
      <div
        class="font-primary text-palette-primary text-2xl pt-4 px-4 font-semibold"
      >
        The Unicorn
      </div>
      <div class="text-lg text-gray-600 p-4 font-primary font-light">
        They exist!
      </div>
      <div
        class="text-palette-dark font-primary font-medium text-base absolute bottom-0 right-0 mb-4 pl-8 pr-4 pb-1 pt-2 bg-palette-lighter  rounded-tl-sm triangle"
      >
        $<span class="text-lg">9.99</span>
      </div>
    </div>
  </a>
</template>
<script>
export default {
  name: "Item",
  props: ["item"],
};
</script>
