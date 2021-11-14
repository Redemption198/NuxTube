<template>
  <div class="flex items-center justify-between pr-4 py-4 bg-black/90 h-16">
    <div class="flex space-x-2">
      <v-header-logo />
      <p class="text-xs ordinal text-white">IT</p>
    </div>

    <div class="flex items-center">
      <div class="flex items-center rounded">
        <input
          type="text"
          placeholder="Search"
          class="bg-black/60 pl-4 z-10 px-80 p-0.5"
        />
        <v-header-search class="px-4 py-0.5 bg-gray-500/30" />
      </div>
      <v-header-search-dictate class="rounded-full bg-black/90 p-1 ml-2" />
    </div>

    <div class="flex items-center space-x-8 mr-4">
      <v-header-create />
      <v-header-apps />
      <v-header-notifications />

      <div>
        <img
          src="https://yt3.ggpht.com/yti/APfAmoGaACucQajG6KuREw6O8_L6JcZSVpZr4BLfLUN6=s88-c-k-c0x00ffffff-no-rj-mo"
          alt="Account Image"
          class="rounded-full h-8"
        />
      </div>
    </div>
  </div>
</template>