<template>
  <div
    class="w-full md:w-1/2 max-w-md border border-palette-lighter bg-white rounded shadow-lg"
  >
    <div class="relative h-96">
      <div class="block absolute inset-0 m-0">
        <img
          src="https://source.unsplash.com/user/erondu/400xauto"
          alt=""
          class="transform duration-500 ease-in-out hover:scale-105"
        />
      </div>
    </div>
    <div class="relative flex border-t border-palette-lighter">
      <button
        aria-label="left-scroll"
        class="h-32 bg-palette-lighter hover:bg-palette-light  absolute left-0 z-10 opacity-75"
      >
        <svg
          aria-hidden="true"
          focusable="false"
          data-prefix="fas"
          data-icon="arrow-left"
          class="svg-inline--fa fa-arrow-left fa-w-14 w-3 mx-1 text-palette-primary"
          role="img"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 448 512"
        >
          <path
            fill="currentColor"
            d="M257.5 445.1l-22.2 22.2c-9.4 9.4-24.6 9.4-33.9 0L7 273c-9.4-9.4-9.4-24.6 0-33.9L201.4 44.7c9.4-9.4 24.6-9.4 33.9 0l22.2 22.2c9.5 9.5 9.3 25-.4 34.3L136.6 216H424c13.3 0 24 10.7 24 24v32c0 13.3-10.7 24-24 24H136.6l120.5 114.8c9.8 9.3 10 24.8.4 34.3z"
          ></path>
        </svg>
      </button>
      <div
        class="flex space-x-1 w-full overflow-auto border-t border-palette-lighter"
      >
        <ItemSliderImage />
      </div>
      <button
        aria-label="right-scroll"
        class="h-32 bg-palette-lighter hover:bg-palette-light  absolute right-0 z-10 opacity-75"
      >
        <svg
          aria-hidden="true"
          focusable="false"
          data-prefix="fas"
          data-icon="arrow-right"
          class="svg-inline--fa fa-arrow-right fa-w-14 w-3 mx-1 text-palette-primary"
          role="img"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 448 512"
        >
          <path
            fill="currentColor"
            d="M190.5 66.9l22.2-22.2c9.4-9.4 24.6-9.4 33.9 0L441 239c9.4 9.4 9.4 24.6 0 33.9L246.6 467.3c-9.4 9.4-24.6 9.4-33.9 0l-22.2-22.2c-9.5-9.5-9.3-25 .4-34.3L311.4 296H24c-13.3 0-24-10.7-24-24v-32c0-13.3 10.7-24 24-24h287.4L190.9 101.2c-9.8-9.3-10-24.8-.4-34.3z"
          ></path>
        </svg>
      </button>
    </div>
  </div>
</template>
<script>
import ItemSliderImage from "@/components/ItemSliderImage.vue";
export default {
  name: "ItemImagePanel",
  components: {
    ItemSliderImage,
  },
};
</script>
