<template>
  <div class="text-sm flex gap-8">
    <!-- Internal Link -->
    <NuxtLink
      to="/"
      class=" text-[rgba(255,255,255,0.5)] hover:text-[rgba(225,225,225,.75)] font-semibold"
    >
      HOME
    </NuxtLink>
    <NuxtLink
      to="/features"
      class=" text-[rgba(255,255,255,0.5)] hover:text-[rgba(225,225,225,.75)] font-semibold"
    >
      FEATURES
    </NuxtLink>
    <NuxtLink
      to="/gallery"
      class=" text-[rgba(255,255,255,0.5)] hover:text-[rgba(225,225,225,.75)] font-semibold"
    >
      GALLERY
    </NuxtLink>
    <NuxtLink
      to="/pricing"
      class=" text-[rgba(255,255,255,0.5)] hover:text-[rgba(225,225,225,.75)] font-semibold"
    >
      PRICING
    </NuxtLink>
    <NuxtLink
      to="/contact"
      class=" text-[rgba(255,255,255,0.5)] hover:text-[rgba(225,225,225,.75)] font-semibold"
    >
      CONTACT</NuxtLink
    >
  </div>
</template>

<style>
.router-link-active {
  border-bottom: 2px solid #cd99d4;
  color: white;
}
</style>
