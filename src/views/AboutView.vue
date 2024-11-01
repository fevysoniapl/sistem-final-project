<script setup lang="ts">
import JoinTeam from '@/components/JoinTeam.vue';
import MainLayout from '@/layouts/MainLayout.vue'
</script>

<template>
  <MainLayout>
    <div class="p-12 relative h-[750px]">
      <div class="absolute top-0 z-10 flex items-center justify-between px-16 py-6">
        <div class="w-1/2 bg-white p-12">
          <p>ABOUT US</p>
          <h2 class="text-5xl font-bold">We are a team of content writers who share their learnings</h2>
        </div>
        <div class="w-1/2 p-12">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
        </div>
      </div>
      <div class="absolute bottom-0 z-10 flex items-center justify-between px-16 py-6 w-full">
        <div class="w-[49%] bg-x-blue py-6 px-16">
          <ul class="flex items-center justify-between">
            <div class="flex flex-col">
              <li class="text-white font-bold text-5xl">12+</li>
              <li class="text-white text-base">Blogs Published</li>
            </div>
            <div class="flex flex-col">
              <li class="text-white font-bold text-5xl">18K+</li>
              <li class="text-white text-base">Views on Finsweet</li>
            </div>
            <div class="flex flex-col">
              <li class="text-white font-bold text-5xl">30K+</li>
              <li class="text-white text-base">Total active Users</li>
            </div>
          </ul>
        </div>
      </div>
      <div class="absolute bottom-0 z-0">
        <img src="@/assets/images/misc/about.png" alt="about background">
      </div>
      <div class="absolute bottom-0 z-0 left-28">
        <img src="@/assets/images/misc/pattern-about.png" alt="pattern">
      </div>
    </div>

    <section class="px-40 py-24 mt-10 max-md:px-5 max-md:mr-0.5 max-md:max-w-full">
      <div class="flex gap-6 max-md:flex-col">
        <article class="flex flex-col ml-5 w-6/12 max-md:ml-0 max-md:w-full">
          <div class="flex flex-col items-start max-md:mt-10 max-md:max-w-full">
            <h2 class="font-semibold text-x-black text-base leading-none uppercase tracking-[3px]">
              OUR MISION
            </h2>
            <h3 class="mt-6 text-3xl font-bold text-x-black tracking-tighter leading-10">
              Creating valuable content for creatives all around the world
            </h3>
            <p class="self-stretch mt-4 text-base leading-7 text-x-mediumgrey max-md:max-w-full">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
            </p>
          </div>
        </article>

        <article class="flex flex-col ml-5 w-6/12 max-md:ml-0 max-md:w-full">
          <div class="flex flex-col items-start max-md:mt-10 max-md:max-w-full">
            <h2 class="font-semibold text-x-black text-base leading-none uppercase tracking-[3px]">
              OUR VISION
            </h2>
            <h3 class="mt-6 text-3xl font-bold text-x-black tracking-tighter leading-10">
              A platform that empowers individuals to improve
            </h3>
            <p class="self-stretch mt-4 text-base leading-7 text-x-mediumgrey max-md:max-w-full">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non blandit massa enim nec. Scelerisque viverra mauris in aliquam sem. At risus viverra adipiscing at in tellus.
            </p>
          </div>
        </article>
      </div>
    </section>

    <section class="flex items-center w-full px-10">
      <div class="flex gap-4 flex-col w-[48%] p-12">
        <h2 class="font-bold tracking-tighter text-4xl text-x-black">Our team of creatives</h2>
        <h4 class="text-2xl leading-8 font-bold text-x-black">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</h4>
        <p class="text-base leading-7 text-x-black">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat.</p>
      </div>
      <div class="relative h-[480px] w-[52%]">
        <div class="absolute top-28 z-10">
          <img src="@/assets/images/misc/shapes-blue.png" alt="shape">
        </div>
        <div class="absolute bottom-0 left-16">
          <img src="@/assets/images/misc/about-1.png" alt="about 1">
        </div>
      </div>
    </section>

    <section class="flex items-center w-full px-10 mt-40">
      <div class="relative h-[520px] w-[52%]">
        <div class="absolute bottom-0 left-40 z-10">
          <img src="@/assets/images/misc/shapes-yellow.png" alt="shape">
        </div>
        <div class="absolute bottom-10 left-12">
          <img src="@/assets/images/misc/about-2.png" alt="about 1">
        </div>
      </div>
      <div class="flex gap-4 flex-col w-[48%] p-12">
        <h2 class="font-bold tracking-tighter text-4xl text-x-black">Why we started this Blog</h2>
        <h4 class="text-2xl leading-8 font-bold text-x-black">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</h4>
        <p class="text-base leading-7 text-x-black">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat.</p>
      </div>
    </section>

    <section class="mt-12 w-full max-md:mt-10 px-20">
      <h2 class="text-4xl font-bold tracking-tighter text-center text-x-black mb-12">
        List of Authors
        </h2>
        <div class="flex flex-col gap-6 max-md:flex-col">
          <div class="flex">
          <div class="flex flex-col w-3/12 max-md:ml-0 max-md:w-full">
            <a href="/author">
            <article class="flex flex-col grow px-14 py-10 w-full leading-none max-md:px-5 max-md:mt-8">
              <img src="@/assets/images/profil/floyd.png" alt="Profile photo of Floyd" class="object-contain self-center w-32 max-w-full rounded-full aspect-square" />
              <h2 class="mt-5 text-3xl font-bold text-center tracking-tighter text-gray-800">Floyd Miles</h2>
              <p class="text-sm text-center mt-1 text-zinc-500">Content Writer @Company</p>
              <ul class="object-contain self-center mt-5 w-28 max-w-full aspect-[6.58] flex gap-4 items-center">
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
            </article>
          </a>
          </div>
          <div class="flex flex-col w-3/12 max-md:ml-0 max-md:w-full">
            <article class="flex flex-col grow px-14 py-10 w-full leading-none max-md:px-5 max-md:mt-8">
              <img src="@/assets/images/profil/Dianne.png" alt="Profile photo of Dianne" class="object-contain self-center w-32 max-w-full rounded-full aspect-square" />
              <h2 class="mt-5 text-3xl font-bold text-center tracking-tighter text-gray-800">Dianne Russell</h2>
              <p class="text-sm text-center mt-1 text-zinc-500">Content Writer @Company</p>
              <ul class="object-contain self-center mt-5 w-28 max-w-full aspect-[6.58] flex gap-4 items-center">
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
            </article>
          </div>
          <div class="flex flex-col w-3/12 max-md:ml-0 max-md:w-full">
            <article class="flex flex-col grow px-14 py-10 w-full leading-none max-md:px-5 max-md:mt-8">
              <img src="@/assets/images/profil/Jenny.png" alt="Profile photo of Jenny" class="object-contain self-center w-32 max-w-full rounded-full aspect-square" />
              <h2 class="mt-5 text-3xl font-bold text-center tracking-tighter text-gray-800">Jenny Wilson</h2>
              <p class="text-sm text-center mt-1 text-zinc-500">Content Writer @Company</p>
              <ul class="object-contain self-center mt-5 w-28 max-w-full aspect-[6.58] flex gap-4 items-center">
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
            </article>
          </div>
          <div class="flex flex-col w-3/12 max-md:ml-0 max-md:w-full">
            <article class="flex flex-col grow px-14 py-10 w-full leading-none max-md:px-5 max-md:mt-8">
              <img src="@/assets/images/profil/Leslie.png" alt="Profile photo of Leslie" class="object-contain self-center w-32 max-w-full rounded-full aspect-square" />
              <h2 class="mt-5 text-3xl font-bold text-center tracking-tighter text-gray-800">Leslie Alexander</h2>
              <p class="text-sm text-center mt-1 text-zinc-500">Content Writer @Company</p>
              <ul class="object-contain self-center mt-5 w-28 max-w-full aspect-[6.58] flex gap-4 items-center">
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
            </article>
          </div>
        </div>

        <div class="flex">
          <div class="flex flex-col w-3/12 max-md:ml-0 max-md:w-full">
            <article class="flex flex-col grow px-14 py-10 w-full leading-none max-md:px-5 max-md:mt-8">
              <img src="@/assets/images/profil/guy.png" alt="Profile photo of Guy" class="object-contain self-center w-32 max-w-full rounded-full aspect-square" />
              <h2 class="mt-5 text-3xl font-bold text-center tracking-tighter text-gray-800">Guy Hawkins</h2>
              <p class="text-sm text-center mt-1 text-zinc-500">Content Writer @Company</p>
              <ul class="object-contain self-center mt-5 w-28 max-w-full aspect-[6.58] flex gap-4 items-center">
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
            </article>
          </div>
          <div class="flex flex-col w-3/12 max-md:ml-0 max-md:w-full">
            <article class="flex flex-col grow px-14 py-10 w-full leading-none max-md:px-5 max-md:mt-8">
              <img src="@/assets/images/profil/eleanor.png" alt="Profile photo of Eleanor" class="object-contain self-center w-32 max-w-full rounded-full aspect-square" />
              <h2 class="mt-5 text-3xl font-bold text-center tracking-tighter text-gray-800">Eleanor Pena</h2>
              <p class="text-sm text-center mt-1 text-zinc-500">Content Writer @Company</p>
              <ul class="object-contain self-center mt-5 w-28 max-w-full aspect-[6.58] flex gap-4 items-center">
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
            </article>
          </div>
          <div class="flex flex-col w-3/12 max-md:ml-0 max-md:w-full">
            <article class="flex flex-col grow px-14 py-10 w-full leading-none max-md:px-5 max-md:mt-8">
              <img src="@/assets/images/profil/robert.png" alt="Profile photo of Robert" class="object-contain self-center w-32 max-w-full rounded-full aspect-square" />
              <h2 class="mt-5 text-3xl font-bold text-center tracking-tighter text-gray-800">Robert Fox</h2>
              <p class="text-sm text-center mt-1 text-zinc-500">Content Writer @Company</p>
              <ul class="object-contain self-center mt-5 w-28 max-w-full aspect-[6.58] flex gap-4 items-center">
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
            </article>
          </div>
          <div class="flex flex-col w-3/12 max-md:ml-0 max-md:w-full">
            <article class="flex flex-col grow px-14 py-10 w-full leading-none max-md:px-5 max-md:mt-8">
              <img src="@/assets/images/profil/jacob.png" alt="Profile photo of Jacob" class="object-contain self-center w-32 max-w-full rounded-full aspect-square" />
              <h2 class="mt-5 text-3xl font-bold text-center tracking-tighter text-gray-800">Jacob Jones</h2>
              <p class="text-sm text-center mt-1 text-zinc-500">Content Writer @Company</p>
              <ul class="object-contain self-center mt-5 w-28 max-w-full aspect-[6.58] flex gap-4 items-center">
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
            </article>
          </div>
        </div>
      </div>
      </section>

    <JoinTeam></JoinTeam>
  </MainLayout>
</template>
