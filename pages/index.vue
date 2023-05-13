<script lang="ts" setup>
// composable
const { t } = useLang()

// meta
definePageMeta({
  layout: 'page',
})



</script>

<template>
  <PageWrapper class="flex-1 flex">
    <div class="background-overlay">
      <div
        class="absolute top-0 left-0 transform translate-x-64 translate-y-4 h-14 w-14 rounded-full bg-gray-900 dark:bg-white"
      ></div>
      <div
        class="absolute hidden md:block top-0 left-0 transform translate-x-18 translate-y-20 h-28 w-28 rounded-full bg-blue-600 linear-wipe"
      ></div>
    </div>
    <PageBody class="flex-1 flex">
      <PageSection class="flex-1 flex items-center">
        <div class="flex-1 md:w-5/8 flex flex-col z-10">
          <h1 class="text-center md:text-left mt-4 animated-text-bg drop-shadow-xl text-8xl block font-black uppercase">
            Social Select 
          </h1>
          <div
            class="flex space-x-4 ml-4 mt-10 justify-center md:justify-start"
          >
            <Button
              size="lg"
              text="Github"
              type="secondary"
              class="font-extrabold"
              href="https://github.com/LunarPunk-Labs/select_screen_social"
            />
          </div>
        </div>
      </PageSection>
    </PageBody>
  </PageWrapper>
</template>

<style lang="scss">
@import '../assets/sass/variables';


</style>
