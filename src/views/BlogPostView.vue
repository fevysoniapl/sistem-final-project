<script setup lang="ts">
import JoinTeam from '@/components/JoinTeam.vue';
import MainLayout from '@/layouts/MainLayout.vue'
</script>

<template>
  <MainLayout>
    <article class="flex flex-col items-start max-w-[666px] mx-auto mt-12 mb-12">
      <header class="flex flex-col items-start gap-2">
        <div class="flex items-center gap-4 w-full">
          <img 
            src="@/assets/images/profil/andrew.png" 
            alt="Profile picture of Andrew Jonson" 
          />
          <div class="flex flex-col items-start leading-tight">
            <h1 class="text-x-yellow text-3xl tracking-tighter font-bold opacity-[0.87]">Andrew Jonson</h1>
            <p class="text-sm text-x-mediumgrey">Posted on 27th January 2022</p>
          </div>
        </div>
      </header>
      
      <h2 class="self-start mt-9 text-5xl font-bold tracking-tighter leading-[64px] text-x-black">
          Step-by-step guide to choosing great font pairs
      </h2>

      <section class="flex items-center gap-2 mt-4">
        <img 
          src="@/assets/images/logo/icon-startup.png" 
          alt="Startup category icon" 
        />
        <p class="text-2xl font-bold ">Startup</p>
      </section>
    </article>

    <section class="image-container mt-12 px-4 mb-12">
      <img 
        src="@/assets/images/misc/overview.png" 
        alt="overview" 
        class="object-contain w-full max-w-[92%] mx-auto aspect-[2.2]" 
      />
    </section>

    <section class="flex justify-center mt-12">
      <article class="flex flex-col items-start text-base leading-7 max-w-[822px] text-x-mediumgrey">
        <header>
          <h1 class="z-10 mt-0 mr-0 text-4xl font-bold tracking-tighter leading-[48px] text-x-black max-md:max-w-full">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod.
          </h1>
        </header>

        <section>
          <p class="mt-4 mr-0 max-md:max-w-full">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non blandit massa enim nec. Scelerisque viverra mauris in aliquam sem. At risus viverra adipiscing at in tellus. Sociis natoque penatibus et magnis dis parturient montes. Ridiculus mus mauris vitae ultricies leo. Neque egestas congue quisque egestas diam. Risus in hendrerit gravida rutrum quisque non.
          </p>
        </section>

        <section>
          <h2 class="mt-12 text-4xl font-bold tracking-tighter leading-[48px] text-x-black max-md:mt-10 max-md:-mr-3.5 max-md:max-w-full">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod.
          </h2>
          <p class="mt-4 max-md:mr-0 max-md:max-w-full">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non blandit massa enim nec. Scelerisque viverra mauris in aliquam sem. At risus viverra adipiscing at in tellus. Sociis natoque penatibus et magnis dis parturient montes. Ridiculus mus mauris vitae ultricies leo. Neque egestas congue quisque egestas diam. Risus in hendrerit gravida rutrum quisque non.
          </p>
          <p class="mt-6 mr-0 max-md:max-w-full">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non blandit massa enim nec. Scelerisque viverra mauris in aliquam sem. At risus viverra adipiscing at in tellus. Sociis natoque penatibus et magnis dis parturient montes. Ridiculus mus mauris vitae ultricies leo. Neque egestas congue quisque egestas diam. Risus in hendrerit gravida rutrum quisque non.
          </p>
        </section>

        <ul class="list-disc pl-1 flex flex-col items-start mt-6 ml-4 text-2xl font-bold leading-[32px] text-x-blackbee text-opacity-[78%] max-md:max-w-full">
          <li>Lorem ipsum dolor sit amet</li>
          <li>Non blandit massa enim nec scelerisque</li>
          <li>Neque egestas congue quisque egestas</li>
        </ul>

        <section>
          <p class="mt-6 max-md:-mr-3.5 max-md:max-w-full">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non blandit massa enim nec. Scelerisque viverra mauris in aliquam sem. At risus viverra adipiscing at in tellus. Sociis natoque penatibus et magnis dis parturient montes. Ridiculus mus mauris vitae ultricies leo. Neque egestas congue quisque egestas diam. Risus in hendrerit gravida rutrum quisque non.
          </p>
        </section>

        <section>
          <h2 class="mt-12 mr-0 text-4xl font-bold tracking-tighter leading-[48px] text-x-black max-md:mt-10 max-md:max-w-full">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod.
          </h2>
          <p class="z-10 mt-4 max-md:mr-0 max-md:max-w-full">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non blandit massa enim nec. Scelerisque viverra mauris in aliquam sem. At risus viverra adipiscing at in tellus. Sociis natoque penatibus et magnis dis parturient montes. Ridiculus mus mauris vitae ultricies leo. Neque egestas congue quisque egestas diam. Risus in hendrerit gravida rutrum quisque non.
          </p>
        </section>
      </article>
    </section>

    <section class="flex flex-col mt-20 px-20">
      <h2 class="text-black text-4xl font-bold leading-[48px] tracking-[-2px]">What to read next</h2>
      <div class="flex gap-7 w-full mt-10">
        <div class="flex flex-col gap-5">
          <img src="@/assets/images/misc/blogpost-1.png" alt="blogpost 1">
          <p class="text-sm text-x-darkgrey">By <span class="text-x-yellow hover:underline">John Doe</span> | Aug 23, 2021</p>
          <h3 class="font-bold text-x-black tracking-[-1px] leading-[40px] text-3xl">A UX Case Study Creating a Studious Environment for Students: </h3>
          <p class="text-x-black text-base leading-7 text-opacity-70">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.</p>
        </div>
        <div class="flex flex-col gap-5">
          <img src="@/assets/images/misc/blogpost-2.png" alt="blogpost 2">
          <p class="text-sm text-x-darkgrey">By <span class="text-x-yellow hover:underline">John Doe</span> | Aug 23, 2021</p>
          <h3 class="font-bold text-x-black tracking-[-1px] leading-[40px] text-3xl">A UX Case Study Creating a Studious Environment for Students: </h3>
          <p class="text-x-black text-base leading-7 text-opacity-70">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.</p>
        </div>
        <div class="flex flex-col gap-5">
          <img src="@/assets/images/misc/blogpost-3.png" alt="blogpost 3">
          <p class="text-sm text-x-darkgrey">By <span class="text-x-yellow hover:underline">John Doe</span> | Aug 23, 2021</p>
          <h3 class="font-bold text-x-black tracking-[-1px] leading-[40px] text-3xl">A UX Case Study Creating a Studious Environment for Students: </h3>
          <p class="text-x-black text-base leading-7 text-opacity-70">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.</p>
        </div>
      </div>
    </section>

    <JoinTeam></JoinTeam>
  </MainLayout>
</template>
