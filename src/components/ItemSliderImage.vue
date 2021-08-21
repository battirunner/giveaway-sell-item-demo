<template>
  <button
    class="relative w-40 h-32 flex-shrink-0 rounded-sm "
    v-for="image in images"
    :key="image.id"
  >
    <div
      style="display: block; overflow: hidden; position: absolute; inset: 0px; box-sizing: border-box; margin: 0px;"
    >
      <img
        alt="drooler-main"
        src="https://source.unsplash.com/user/erondu/160x120"
        decoding="async"
        class=""
        style="position: absolute; inset: 0px; box-sizing: border-box; padding: 0px; border: none; margin: auto; display: block; width: 0px; height: 0px; min-width: 100%; max-width: 100%; min-height: 100%; max-height: 100%;"
        sizes="100vw"
        srcset="https://source.unsplash.com/user/erondu/160x120"
      />
    </div>
  </button>
</template>
<script>
// import { defineComponent } from '@vue/composition-api'

export default {
  name: "ItemSliderImage",
  data() {
    return {
      images: [],
    };
  },
  created() {
    this.images = [
      {
        id: 1,
        imgSrc: "https://source.unsplash.com/user/erondu/160x120",
      },
      {
        id: 2,
        imgSrc: "https://source.unsplash.com/user/erondu/160x120",
      },
      {
        id: 3,
        imgSrc: "https://source.unsplash.com/user/erondu/160x120",
      },
      {
        id: 4,
        imgSrc: "https://source.unsplash.com/user/erondu/160x120",
      },
      {
        id: 5,
        imgSrc: "https://source.unsplash.com/user/erondu/160x120",
      },
    ];
  },
};
</script>
