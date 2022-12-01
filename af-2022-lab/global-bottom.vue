<template>
  <footer class="absolute bottom-0 left-0 right-0 w-full">
    <div class="flex justify-left w-full p-2">
      <div
        class="flex flex-col gap-2 bg-light-background dark:bg-dark-background bg-opacity-60 p-2 rounded-md"
      >
        <span class="text-sm"><logos-twitter class="mr-1" />@Julio_PDX</span>
        <span class="text-sm"><mdi-public class="mr-1" />juliopdx.com</span>
        <span class="text-sm"><mdi-pencil class="mr-1" />{{ $slidev.configs.author }}</span>
      </div>
    </div>
    <!-- <div class="border-bar"></div> -->
  </footer>
</template>

<style>
.border-bar {
  @apply h-0.5 w-full mb-1 bg-accent;
  box-shadow: 0 0 3px 0.5px var(--accent);
}
</style>