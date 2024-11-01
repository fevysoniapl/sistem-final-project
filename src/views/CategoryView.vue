<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
</script>

<template>
  <MainLayout>
    <section class="flex flex-col text-center">
      <header class="flex flex-col justify-center items-center p-20 w-full max-md:px-5 max-md:max-w-full">
        <div class="flex flex-col items-center max-w-full w-[472px]">
          <h1 class="text-6xl font-bold tracking-tighter text-x-black max-md:text-4xl">
            Business
          </h1>
          <p class="self-stretch mt-4 leading-7 text-x-mediumgrey max-md:max-w-full">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore.
          </p>
          <nav class="mt-8 font-medium leading-none uppercase tracking-[3px]" aria-label="breadcrumb">
            <a href="/blog" class="hover:underline">Blog</a>
            <span aria-hidden="true"> &gt; </span>
            <a href="/category" class="hover:underline" aria-current="page">Business</a>
          </nav>
        </div>
      </header>
    </section>

    <section class="flex flex-col items-center p-8 w-full">
      <div class="flex flex-row gap-5 w-full max-w-7xl">
        <main class="w-3/4">
          <div class="space-y-8">
            <article class="flex gap-5 mr-6">
              <img src="@/assets/images/misc/category.png" alt="Article thumbnail" class="size-full w-1/3">
              <div class="w-2/3 flex flex-col justify-center px-4">
                <span class="text-x-yellow text-base tracking-[3px] font-semibold uppercase">Business</span>
                <h2 class="text-4xl text-x-black font-bold mt-2 tracking-[-2px] leading-[48px]">Top 6 free website mockup tools 2022</h2>
                <p class="text-x-mediumgrey leading-7 mt-2">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non blandit massa enim nec.</p>
              </div>
            </article>
  
            <article class="flex gap-5 mr-6">
              <img src="@/assets/images/misc/category.png" alt="Article thumbnail" class="size-full w-1/3">
              <div class="w-2/3 flex flex-col justify-center px-4">
                <span class="text-x-yellow text-base tracking-[3px] font-semibold uppercase">Business</span>
                <h2 class="text-4xl text-x-black font-bold mt-2 tracking-[-2px] leading-[48px]">Step-by-step guide to choosing great font pairs</h2>
                <p class="text-x-mediumgrey leading-7 mt-2">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non blandit massa enim nec.</p>
              </div>
            </article>
  
            <article class="flex gap-5 mr-6">
              <img src="@/assets/images/misc/category.png" alt="Article thumbnail" class="size-full w-1/3">
              <div class="w-2/3 flex flex-col justify-center px-4">
                <span class="text-x-yellow text-base tracking-[3px] font-semibold uppercase">Business</span>
                <h2 class="text-4xl text-x-black font-bold mt-2 tracking-[-2px] leading-[48px]">Ten free foogle fonts that you should use</h2>
                <p class="text-x-mediumgrey leading-7 mt-2">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non blandit massa enim nec.</p>
              </div>
            </article>
  
            <article class="flex gap-5 mr-6">
              <img src="@/assets/images/misc/category.png" alt="Article thumbnail" class="size-full w-1/3">
              <div class="w-2/3 flex flex-col justify-center px-4">
                <span class="text-x-yellow text-base tracking-[3px] font-semibold uppercase">Business</span>
                <h2 class="text-4xl text-x-black font-bold mt-2 tracking-[-2px] leading-[48px]">What did I learn from doing 50+ design sprints?</h2>
                <p class="text-x-mediumgrey leading-7 mt-2">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non blandit massa enim nec.</p>
              </div>
            </article>
          </div>
        </main>
  
        <aside class="w-1/4 space-y-10 ml-10">
          <section>
            <h3 class="text-4xl font-bold tracking-[-2px]">Categories</h3>
            <div class="mt-4 space-y-5">
              <button class="flex items-center gap-3 w-full p-4 border border-solid border-x-ashgrey hover:bg-x-blue group" style="border-width: 1.5px;">
                <div class="ml-1 bg-white rounded-lg inline-block">
                  <img loading="lazy" src="@/assets/images/logo/icon-startup.png" alt="Startup Icon" class="w-12 aspect-square scale-50" />
                </div>
                <p class="text-x-black font-bold text-3xl group-hover:text-white tracking-[-1px]">Startup</p>
              </button>
              <button class="flex items-center gap-3 w-full p-4 border border-solid border-x-ashgrey hover:bg-x-blue group" style="border-width: 1.5px;">
                <div class="ml-1 bg-white rounded-lg inline-block">
                  <img loading="lazy" src="@/assets/images/logo/icon-business.png" alt="Business Icon" class="w-12 aspect-square" />
                </div>
                <p class="text-x-black font-bold text-3xl group-hover:text-white tracking-[-1px]">Business</p>
              </button>
              <button class="flex items-center gap-3 w-full p-4 border border-solid border-x-ashgrey hover:bg-x-blue group" style="border-width: 1.5px;">
                <div class="ml-1 bg-white rounded-lg inline-block">
                  <img loading="lazy" src="@/assets/images/logo/icon-economy.png" alt="Economy Icon" class="w-12 aspect-square" />
                </div>
                <p class="text-x-black font-bold text-3xl group-hover:text-white tracking-[-1px]">Economy</p>
              </button>
              <button class="flex items-center gap-3 w-full p-4 border border-solid border-x-ashgrey hover:bg-x-blue group" style="border-width: 1.5px;">
                <div class="ml-1 bg-white rounded-lg inline-block">
                  <img loading="lazy" src="@/assets/images/logo/icon-tech.png" alt="Technology Icon" class="w-12 aspect-square" />
                </div>
                <p class="text-x-black font-bold text-3xl group-hover:text-white tracking-[-1px]">Technology</p>
              </button>
            </div>
          </section>
  
          <section>
            <h3 class="text-4xl font-bold tracking-[-2px] mt-8">All Tags</h3>
            <div class="flex flex-wrap gap-2.5 mt-4">
              <button class="px-9 py-2 border-2 border-x-mediumgrey border-opacity-70 rounded-full text-sm text-x-black font-bold hover:bg-x-mediumgrey hover:bg-opacity-70">Business</button>
              <button class="px-9 py-2 border-2 border-x-mediumgrey border-opacity-70 rounded-full text-sm text-x-black font-bold hover:bg-x-mediumgrey hover:bg-opacity-70">Experience</button>
              <button class="px-9 py-2 border-2 border-x-mediumgrey border-opacity-70 rounded-full text-sm text-x-black font-bold hover:bg-x-mediumgrey hover:bg-opacity-70">Screen</button>
              <button class="px-9 py-2 border-2 border-x-mediumgrey border-opacity-70 rounded-full text-sm text-x-black font-bold hover:bg-x-mediumgrey hover:bg-opacity-70">Technology</button>
              <button class="px-9 py-2 border-2 border-x-mediumgrey border-opacity-70 rounded-full text-sm text-x-black font-bold hover:bg-x-mediumgrey hover:bg-opacity-70">Marketing</button>
              <button class="px-9 py-2 border-2 border-x-mediumgrey border-opacity-70 rounded-full text-sm text-x-black font-bold hover:bg-x-mediumgrey hover:bg-opacity-70">Life</button>
            </div>
          </section>
        </aside>
      </div>
    </section>
  </MainLayout>
</template>