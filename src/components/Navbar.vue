<template>
  <header class="border-b border-palette-lighter sticky top-0 z-20 bg-white">
    <div
      class="flex items-center justify-between mx-auto max-w-6xl px-6 pb-2 pt-4 md:pt-6"
    >
      <a class="cursor-pointer" href="">
        <h1 class="flex no-underline">
          <img
            class="h-8 w-8 mr-1 object-contain"
            src="/assets/icon.png"
            alt=""
          />
          <span class="text-xl font-primary font-bold tracking-tight pt-1"
            >Doggy Stickers</span
          >
        </h1>
      </a>
      <div id="nav">
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link> |
        <!-- <router-link to="/item/:id">Item</router-link> -->
      </div>
      <div>
        <a class="relative" href="">
          <svg
            aria-hidden="true"
            focusable="false"
            data-prefix="fas"
            data-icon="shopping-cart"
            class="svg-inline--fa fa-shopping-cart fa-w-18 text-palette-primary w-6 m-auto"
            role="img"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 576 512"
          >
            <path
              fill="currentColor"
              d="M528.12 301.319l47.273-208C578.806 78.301 567.391 64 551.99 64H159.208l-9.166-44.81C147.758 8.021 137.93 0 126.529 0H24C10.745 0 0 10.745 0 24v16c0 13.255 10.745 24 24 24h69.883l70.248 343.435C147.325 417.1 136 435.222 136 456c0 30.928 25.072 56 56 56s56-25.072 56-56c0-15.674-6.447-29.835-16.824-40h209.647C430.447 426.165 424 440.326 424 456c0 30.928 25.072 56 56 56s56-25.072 56-56c0-22.172-12.888-41.332-31.579-50.405l5.517-24.276c3.413-15.018-8.002-29.319-23.403-29.319H218.117l-6.545-32h293.145c11.206 0 20.92-7.754 23.403-18.681z"
            ></path>
          </svg>
        </a>
      </div>
    </div>
  </header>
  <main>
    <router-view />
  </main>
</template>
