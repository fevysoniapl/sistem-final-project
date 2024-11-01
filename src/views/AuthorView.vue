<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
</script>

<template>
  <MainLayout>
    <section class="px-48 mt-28 flex flex-col">
      <div class="flex gap-10 items-center">
        <img src="@/assets/images/misc/author.png" alt="author"/>
        <div class="flex flex-col gap-5 mr-36">
          <h1 class="text-5xl font-bold text-x-black tracking-[-2px] leading-[64px]">Hey there, I'm Andrew Jonhson and welcome to my Blog</h1>
          <p class="text-base text-x-mediumgrey leading-7">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non blandit massa enim nec. Scelerisque viverra mauris in aliquam sem. At risus viverra adipiscing at in tellus.</p>
          <ul class="object-contain w-28 max-w-full aspect-[6.58] flex gap-4">
            <li>
              <img src="@/assets/images/logo/black-facebook.png" alt="Logo Facebook" />
            </li>
            <li>
              <img src="@/assets/images/logo/black-twitter.png" alt="Logo Twitter" />
            </li>
            <li>
              <img src="@/assets/images/logo/black-instagram.png" alt="Logo Instagram" />
            </li>
            <li>
              <img src="@/assets/images/logo/black-linkedin.png" alt="Logo Linkedin" />
            </li>
          </ul>
        </div>
      </div>
      <img src="@/assets/images/misc/pattern-author.png" alt="author" class="mt-20"/>
    </section>
    <section class="flex flex-col px-48 mt-28 w-full">
        <header>
            <h1 class="self-start text-5xl font-bold tracking-tighter leading-none text-x-black">
                My Posts
            </h1>
        </header>
        <div class="flex flex-col gap-16 mt-16">
            <article class="flex items-center">
                <img src="@/assets/images/misc/author-1.png" alt="blog 1" class="flex w-[36%]"/>
                <div class="flex flex-col w-[64%] ml-16 text-left gap-5 mr-24">
                    <p class="font-semibold text-x-yellow text-base uppercase tracking-[3px]">business</p>
                    <h2 class="text-4xl font-bold tracking-[-2px]">Font sizes in UI design: The complete guide to follow</h2>
                    <p class="text-x-mediumgrey text-base leading-[28px]">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                </div>
            </article>
            <article class="flex items-center">
                <img src="@/assets/images/misc/author-2.png" alt="blog 2" class="flex w-[36%]"/>
                <div class="flex flex-col w-[64%] ml-16 text-left gap-5 mr-24">
                    <p class="font-semibold text-x-yellow text-base uppercase tracking-[3px]">economy</p>
                    <h2 class="text-4xl font-bold tracking-[-2px]">How to build rapport with your web design clients</h2>
                    <p class="text-x-mediumgrey text-base leading-[28px]">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                </div>
            </article>
        </div>
    </section>
  </MainLayout>
</template>