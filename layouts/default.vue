<script setup lang="ts"></script>

<template>
  <div>
    <!-- === Sidebar === -->
    <div class="fixed inset-y-0 z-50 hidden h-full w-56 md:block">
      <slot />
    </div>
  </div>
</template>

<style lang="css" scoped></style>
