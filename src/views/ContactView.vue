<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
</script>

<template>
  <MainLayout>
    <section class="flex w-full justify-center">
      <div class="mt-20 w-[768px] items-center flex flex-col gap-5">
        <p class="text-base uppercase text-x-black font-bold tracking-[3px] leading-[20px]">contact us</p>
        <h1 class="text-5xl text-x-black font-bold tracking-[-2px] leading-[64px]">Let's Start a Conversation</h1>
        <p class="text-base text-x-mediumgrey leading-7 text-center">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim.</p>
      </div>
    </section>

    <section class="flex w-full mt-16 justify-center">
      <div class="w-[768px] bg-x-yellow flex gap-5 p-6">
        <div class="w-1/2 flex flex-col p-5">
          <p class="text-sm leading-[20px] text-x-darkgrey text-opacity-60">Working hours</p>
          <div class="h-[1px] bg-x-darkgrey bg-opacity-10 my-3"></div>
          <h5 class="text-xl font-bold text-x-darkgrey leading-[32px]">Monday To Friday</h5>
          <h5 class="text-xl font-bold text-x-darkgrey leading-[32px]">9:00 AM to 8:00 PM</h5>
          <p class="text-base text-x-darkgrey text-opacity-60 leading-[28px]">Our Support Team is available 24/7</p>
        </div>
        <div class="w-1/2 flex flex-col p-5">
          <p class="text-sm leading-[20px] text-x-darkgrey text-opacity-60">Contact Us</p>
          <div class="h-[1px] bg-x-darkgrey bg-opacity-10 my-3"></div>
          <h5 class="text-xl font-bold text-x-darkgrey leading-[32px]">020 7993 2905</h5>
          <p class="text-base text-x-darkgrey text-opacity-60 leading-[28px]">hello@finsweet.com</p>
        </div>
      </div>
    </section>

    <section class="flex w-full mt-9 justify-center">
      <div class="w-[768px]">
        <form action="">
          <label for="fullName" class="sr-only">Full Name</label>
          <input type="text" id="fullName" name="fullName" placeholder="Full Name" required
            class="gap-2.5 self-stretch p-6 w-full text-base leading-7 text-x-black rounded-sm border border-solid border-x-mediumgrey border-opacity-50" />

          <label for="email" class="sr-only">Your Email</label>
          <input type="email" id="email" name="email" placeholder="Your Email" required
            class="gap-2.5 self-stretch p-6 w-full mt-4 text-base leading-7 text-x-black rounded-sm border border-solid border-x-mediumgrey border-opacity-50" />

          <div class="flex flex-wrap gap-4 items-center mt-3.5 w-full">
            <div class="flex-1">
              <label for="province" class="sr-only">Province</label>
              <select id="province" name="province" required
                class="w-full p-6 border border-solid border-x-mediumgrey border-opacity-50 text-x-black">
                <option value="">Province</option>
              </select>
            </div>
            <div class="flex-1">
              <label for="city" class="sr-only">City</label>
              <select id="city" name="city" required
                class="w-full p-6 border border-solid border-x-mediumgrey border-opacity-50 text-x-black">
                <option value="">City</option>
              </select>
            </div>
          </div>

          <label for="message" class="sr-only">Message</label>
          <textarea id="message" name="message" placeholder="Message" required
            class="gap-2.5 px-6 pt-6 pb-24 mt-5 w-full text-base leading-7 text-x-black rounded-sm border border-solid border-x-mediumgrey border-opacity-50 min-h-[144px]"></textarea>

          <button type="submit"
            class="w-full px-16 py-4 mt-4 text-2xl font-bold text-x-black bg-x-blue hover:bg-x-yellow">
            Send Message
          </button>
        </form>
      </div>
    </section>
  </MainLayout>
</template>