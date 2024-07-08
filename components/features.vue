<template>
  <div class="bg-[#faf6fb] py-20">
    <div class="container mx-auto">
      <div class="section-content text-center mb-14 px-4">
        <p class="text-neutral-400 text-xs font-normal">HIGHLIGHTS</p>
        <h3 class="text-[#633991] text-3xl font-semibold font-sans">
          Features you love
        </h3>
      </div>

      <div class="cards flex justify-between">
        <div
          class="card-border bg-white rounded-r flex p-5 drop-shadow-xl mx-4"
        >
          <div class="pr-4">
            <NuxtImg
              src="../public/images/smile.png"
              height="100%"
              width="100%"
            />
          </div>

          <div>
            <p class="text-xl mb-3 text-[#633991] font-semibold">Simple</p>
            <p class="text-sm break-words font-normal text-[#959094]">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer
              rutrum, urna eu pellentesque
            </p>
          </div>
        </div>

        <div
          class="card-border bg-white rounded-r flex p-5 drop-shadow-xl mx-4"
        >
          <div class="pr-4">
            <NuxtImg
              src="../public/images/setting.png"
              height="100%"
              width="100%"
            />
          </div>

          <div>
            <p class="text-xl mb-3 text-[#633991] font-semibold">Simple</p>
            <p class="text-sm break-words font-normal text-[#959094]">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer
              rutrum, urna eu pellentesque
            </p>
          </div>
        </div>

        <div
          class="card-border bg-white rounded-r flex p-5 drop-shadow-xl mx-4"
        >
          <div class="pr-4">
            <NuxtImg
              src="../public/images/lock.png"
              height="100%"
              width="100%"
            />
          </div>

          <div>
            <p class="text-xl mb-3 text-[#633991] font-semibold">Simple</p>
            <p class="text-sm break-words font-normal text-[#959094]">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer
              rutrum, urna eu pellentesque
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style>
.card-border::before {
  content: "";
  position: absolute;
  width: 3px;
  background: linear-gradient(to bottom, #9477b4 0%, #fc73b4 100%);
  top: 0;
  bottom: 0;
  left: 0;
}
</style>
