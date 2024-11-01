<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
import JoinTeam from '@/components/JoinTeam.vue'
</script>

<template>
  <MainLayout>
    <article class="p-20 w-full">
        <div class="flex gap-5">
        <section class="flex flex-col w-[55%]">
            <div class="flex flex-col items-start self-stretch my-auto w-full font-medium">
            <span class="text-base leading-0 text-x-black uppercase tracking-[3px]">Featured Post</span>
            <h1 class="self-stretch mt-5 text-4xl font-bold tracking-[-2px] leading-12 text-x-black">
                Step-by-step guide to choosing great font pairs
            </h1>
            <time class="mt-4 text-sm leading-none text-x-darkgrey">
                By <a href="#" class="text-x-yellow hover:underline">John Doe</a> | May 23, 2022
            </time>
            <p class="self-stretch mt-4 text-base leading-7 text-x-mediumgrey">
                Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
                Excepteur sint occaecat cupidatat non proident.
            </p>
            <a href="/blog-post">
                <button class="gap-3 px-12 py-4 mt-8 text-lg font-bold leading-none text-white bg-x-blue hover:bg-x-yellow">
                    Read More {{ ' >' }}
                </button>
            </a>
            </div>
        </section>
        <section class="flex flex-col ml-5 w-[45%]">
            <img 
            src="@/assets/images/misc/blog.png"
            alt="Featured post"
            class="object-contain grow w-full aspect-[1.43]" />
        </section>
        </div>
    </article>

    <section class="flex flex-col px-20 mt-16 w-full">
        <header>
            <h1 class="self-start text-5xl font-bold tracking-tighter leading-none text-x-black">
                All posts
            </h1>
        </header>
        <div class="flex flex-col gap-16 mt-16">
            <article class="flex items-center">
                <img src="@/assets/images/misc/blog-1.png" alt="blog 1" class="flex w-[36%]"/>
                <div class="flex flex-col w-[64%] ml-16 text-left gap-5 mr-24">
                    <p class="font-semibold text-x-yellow text-base uppercase tracking-[3px]">startup</p>
                    <h2 class="text-4xl font-bold tracking-[-2px]">Design tips for designers that cover everything you need</h2>
                    <p class="text-x-mediumgrey text-base leading-[28px]">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.</p>
                </div>
            </article>
            <article class="flex items-center">
                <img src="@/assets/images/misc/blog-2.png" alt="blog 2" class="flex w-[36%]"/>
                <div class="flex flex-col w-[64%] ml-16 text-left gap-5 mr-24">
                    <p class="font-semibold text-x-yellow text-base uppercase tracking-[3px]">startup</p>
                    <h2 class="text-4xl font-bold tracking-[-2px]">How to build rapport with your web design clients</h2>
                    <p class="text-x-mediumgrey text-base leading-[28px]">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.</p>
                </div>
            </article>
            <article class="flex items-center">
                <img src="@/assets/images/misc/blog-3.png" alt="blog 3" class="flex w-[36%]"/>
                <div class="flex flex-col w-[64%] ml-16 text-left gap-5 mr-24">
                    <p class="font-semibold text-x-yellow text-base uppercase tracking-[3px]">startup</p>
                    <h2 class="text-4xl font-bold tracking-[-2px]">Logo design trends to avoid in 2022</h2>
                    <p class="text-x-mediumgrey text-base leading-[28px]">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.</p>
                </div>
            </article>
            <article class="flex items-center">
                <img src="@/assets/images/misc/blog-4.png" alt="blog 4" class="flex w-[36%]"/>
                <div class="flex flex-col w-[64%] ml-16 text-left gap-5 mr-24">
                    <p class="font-semibold text-x-yellow text-base uppercase tracking-[3px]">startup</p>
                    <h2 class="text-4xl font-bold tracking-[-2px]">8 Figma design systems you can download for free today</h2>
                    <p class="text-x-mediumgrey text-base leading-[28px]">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.</p>
                </div>
            </article>
            <article class="flex items-center">
                <img src="@/assets/images/misc/blog-1.png" alt="blog 5" class="flex w-[36%]"/>
                <div class="flex flex-col w-[64%] ml-16 text-left gap-5 mr-24">
                    <p class="font-semibold text-x-yellow text-base uppercase tracking-[3px]">startup</p>
                    <h2 class="text-4xl font-bold tracking-[-2px]">Font sizes in UI design: The complete guide to follow</h2>
                    <p class="text-x-mediumgrey text-base leading-[28px]">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.</p>
                </div>
            </article>
        </div>
    </section>

    <nav class="flex justify-center gap-4 mt-16 w-full font-bold text-center max-md:mt-8">
        <button class="text-2xl leading-none text-zinc-500">
          {{ '<' }} Prev
        </button>
        <button class="text-3xl tracking-tighter leading-none text-gray-800">
          Next {{ '>' }}
        </button>
    </nav>

    <section class="px-20 py-12 max-md:px-5">
        <h2 class="text-4xl font-bold tracking-tighter text-left text-x-black mb-12">
          All Categories
        </h2>
        <div class="grid grid-cols-4 gap-8 max-md:grid-cols-1">
          <!-- Category Cards -->
          <a href="/category">
            <article class="border border-opacity-30 border-x-mediumgrey p-8 hover:bg-x-blue hover:text-white transition-colors group">
              <div class="bg-white rounded-lg inline-block">
                <img loading="lazy"
                src="@/assets/images/logo/icon-business.png"
                alt="Business Icon" class="w-12 aspect-square" />
              </div>
              <h3 class="mt-4 text-3xl font-bold text-x-black group-hover:text-white">Business</h3>
              <p class="mt-1 text-x-mediumgrey text-base group-hover:text-white">
                Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
              </p>
            </article>
          </a>
          <article class="border border-opacity-30 border-x-mediumgrey p-8 hover:bg-x-blue hover:text-white transition-colors group">
            <div class="bg-white rounded-lg inline-block">
              <img loading="lazy"
              src="@/assets/images/logo/icon-startup.png"
              alt="Startup Icon" class="w-12 aspect-square scale-50" />
            </div>
            <h3 class="mt-4 text-3xl font-bold text-x-black group-hover:text-white">Startup</h3>
            <p class="mt-1 text-x-mediumgrey text-base group-hover:text-white">
              Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
            </p>
          </article>
          <article class="border border-opacity-30 border-x-mediumgrey p-8 hover:bg-x-blue hover:text-white transition-colors group">
            <div class="bg-white rounded-lg inline-block">
              <img loading="lazy"
              src="@/assets/images/logo/icon-economy.png"
              alt="Economy Icon" class="w-12 aspect-square" />
            </div>
            <h3 class="mt-4 text-3xl font-bold text-x-black group-hover:text-white">Economy</h3>
            <p class="mt-1 text-x-mediumgrey text-base group-hover:text-white">
              Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
            </p>
          </article>
          <article class="border border-opacity-30 border-x-mediumgrey p-8 hover:bg-x-blue hover:text-white transition-colors group">
            <div class="bg-white rounded-lg inline-block">
              <img loading="lazy"
              src="@/assets/images/logo/icon-tech.png"
              alt="Technology Icon" class="w-12 aspect-square" />
            </div>
            <h3 class="mt-4 text-3xl font-bold text-x-black group-hover:text-white">Technology</h3>
            <p class="mt-1 text-x-mediumgrey text-base group-hover:text-white">
              Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
            </p>
          </article>
        </div>
      </section>

      <JoinTeam></JoinTeam>
  </MainLayout>
</template>
