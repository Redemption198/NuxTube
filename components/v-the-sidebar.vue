<template>
  <div class="flex items-center h-screen bg-black/90 flex-col">
    <div class="m-5">
      <v-header-menu class="mx-2" />
    </div>
    <v-sidebar-item>
      <v-sidebar-home class="m-auto" />
      <p class="text-center text-[0.6rem] font-bold text-white">Home</p>
    </v-sidebar-item>
    <v-sidebar-item>
      <v-sidebar-explore class="m-auto" />
      <p class="text-center text-[0.6rem] font-bold text-white">Explore</p>
    </v-sidebar-item>
    <v-sidebar-item>
      <v-sidebar-subscriptions class="m-auto" />
      <p class="text-center text-[0.6rem] font-bold text-white">
        Subscriptions
      </p>
    </v-sidebar-item>
    <v-sidebar-item>
      <v-sidebar-collections class="m-auto" />
      <p class="text-center text-[0.6rem] font-bold text-white">Collections</p>
    </v-sidebar-item>
  </div>
</template>