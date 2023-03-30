<script setup lang="ts"></script>

<template>
  <nav
    class="top-0 left-0 flex items-center justify-between min-w-full px-10 py-5 lg:absolute bg-slate-100"
  >
    <div class="flex items-center gap-2 cursor-pointer">
      <div class="w-16 h-10 bg-slate-900 rounded-xl"></div>
      <span class="text-xl font-bold">Your Brand</span>
    </div>

    <div class="items-center hidden gap-6 lg:flex">
      <span class="underline duration-200 cursor-pointer opacity-60 hover:opacity-80"
        >Services</span
      >
      <span class="underline duration-200 cursor-pointer opacity-60 hover:opacity-80">Product</span>
      <span class="underline duration-200 cursor-pointer opacity-60 hover:opacity-80">Blog</span>
      <span class="underline duration-200 cursor-pointer opacity-60 hover:opacity-80"
        >About us</span
      >
    </div>

    <button
      class="hidden px-5 py-2 font-semibold duration-200 bg-green-400 rounded-xl hover:bg-green-500 lg:flex"
    >
      Get a demo
    </button>
  </nav>
</template>
