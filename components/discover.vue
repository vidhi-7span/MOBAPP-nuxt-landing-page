<template>
  <div class="py-20">
    <div class="container mx-auto">
      <div class="px-4">
        <div class="container flex justify-end">
          <div class="lg:w-1/2 px-4">
            <NuxtImg
              src="../public/images/phone.png"
              class="bg-white w-16 rounded-sm mb-6 customShadow py-2 px-4"
            />

            <p class="text-[45px] font-light mb-4 customHeader">
              Discover our App
            </p>

            <p class="mb-6 descriptionColor text-wrap">
              Lorem ipsum dolor sit amet consectetur, adipisicing elit.
              Obcaecati vel exercitationem eveniet vero maxime ratione
            </p>

            <NuxtLink
              class="text-white font-medium text-xs uppercase cursor-pointer customButton"
            >
              read more
            </NuxtLink>
          </div>
        </div>
        <div class="block -mt-36 relative z-[-1px]">
          <NuxtImg
            src="../public/images/perspective.png"
            class="max-w-full h-auto align-middle"
          />
        </div>
      </div>
    </div>
  </div>
</template>
