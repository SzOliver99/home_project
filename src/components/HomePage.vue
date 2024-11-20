<script setup>
  import Navbar from "./Navbar.vue"
</script>

<template>
  <div id="container" class="flex flex-col">
    <div id="our-team" class="flex flex-col pt-10 gap-5 items-center">
      <h2 class="text-blue-600 text-lg font-semibold">Meet Our Team</h2>
      <p class="text-sm">Our team is a mix of talented individuals who bring unique skills and perspectives to the table. Get to know some of the faces behind the work.</p>
      <div class="flex gap-5">
        <div class="flex flex-col items-center">
          <img class="rounded-full h-1/2 mb-2" src="https://placehold.jp/150x150.png" alt="">
          <p class="font-bold">John Doe</p>
          <p class="text-sm">Lead Developer</p>
        </div>
        <div class="flex flex-col items-center">
          <img class="rounded-full h-1/2 mb-2" src="https://placehold.jp/150x150.png" alt="">
          <p class="font-bold">Jane Smith</p>
          <p class="text-sm">UI/UX Designer</p>
        </div>
        <div class="flex flex-col items-center">
          <img class="rounded-full h-1/2 mb-2" src="https://placehold.jp/150x150.png" alt="">
          <p class="font-bold">Samuel Lee</p>
          <p class="text-sm">Product Manager</p>
        </div>
      </div>
    </div>
    <div class="flex flex-col items-center w-full bg-blue-50 py-10">
      <img class="w-1/3 rounded-lg mb-5 shadow-lg" src="https://placehold.jp/800x400.png" alt="">
      <p class="text-sm">A beautiful placeholder image to showcase design.</p>
    </div>
    <div class="flex flex-col items-center w-full bg-blue-200 py-10">
      <h2 class="text-blue-600 text-lg font-semibold mb-3">Get in Touch</h2>
      <p class="text-sm mb-2">Have questions or want to know more? fell free to reach out to us.</p>
      <button class="px-4 py-1 rounded-lg bg-blue-700 text-sm text-white">Contact Us</button>
    </div>
    <div class="flex flex-col items-center bg-blue-50 h-full">
      <div class="flex flex-col items-center bg-white py-10 px-3">
        <h2 class="text-lg font-bold mb-5">Features</h2>
        <div class="flex gap-5">
          <div class="bg-blue-200 p-3 rounded-lg">
            <h3 class="font-semibold">Feature 1</h3>
            <p class="text-sm">Detailed description of feature 1.</p>
          </div>
          <div class="bg-blue-200 p-3 rounded-lg">
            <h3 class="font-semibold">Feature 1</h3>
            <p class="text-sm">Detailed description of feature 1.</p>
          </div>
          <div class="bg-blue-200 p-3 rounded-lg">
            <h3 class="font-semibold">Feature 1</h3>
            <p class="text-sm">Detailed description of feature 1.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>