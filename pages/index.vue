<template>
  <div class="fixed">
    <div class="flex">
      <v-the-sidebar />
      <div class="flex-1">
        <v-the-header />
        <v-the-tags />
        <div class="bg-black/95 overflow-y-scroll h-full">
          <div class="m-6 grid grid-cols-5 grid-rows-2 gap-x-4 gap-y-8">
            <v-video-card />
            <v-video-card />
            <v-video-card />
            <v-video-card />
            <v-video-card />
            <v-video-card />
            <v-video-card />
            <v-video-card />
            <v-video-card />
            <v-video-card />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>
