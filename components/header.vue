<template>
  <div
    id="header"
    class="bg-gradient-to-r from-violet-900 to-pink-600 sticky top-0 transition-all duration-300"
    :class="isCompact ? 'py-0 shadow-2xl' : 'py-4 shadow-none'"
  >
    <div class="container mx-auto">
      <div class="flex flex-row flex-nowrap items-center py-2 px-4">
        <div class="cursor-pointer">
          <NuxtImg src="../public/images/logo.png" alt="Logo" />
        </div>
        <div class="flex basis-auto flex-grow items-cente px-8 py-2">
          <div class="flex flex-row ml-auto items-center">
            <Nav />
          </div>
          <button class="ml-8 py-1.5 px-5 text-white text-xs border rounded">
            DOWNLOAD
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { ref, onMounted, onBeforeUnmount } from "vue";

const isCompact = ref(false);

onMounted(() => {
  const handleScroll = () => {
    isCompact.value = window.scrollY > 50;
  };

  window.addEventListener("scroll", handleScroll);

  onBeforeUnmount(() => {
    window.removeEventListener("scroll", handleScroll);
  });
});
</script>
