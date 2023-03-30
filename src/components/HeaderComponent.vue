<script lang="ts" setup>
import 'boxicons'
</script>

<template>
  <header class="grid items-center min-h-screen gap-10 lg:grid-cols-2 bg-slate-100">
    <div class="flex flex-col gap-10 px-10">
      <h2 class="text-5xl font-extrabold">Plan joint ventures for desired targets</h2>
      <p class="opacity-70">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Exercitationem ratione soluta
        debitis voluptatibus necessitatibus molestias nostrum rem molestiae tenetur perspiciatis!
      </p>

      <button class="flex items-center gap-2 text-xl font-semibold">
        <div class="flex items-center justify-center p-1 bg-green-400 rounded-full">
          <box-icon name="right-arrow-alt" />
        </div>
        <span class="border-b-2 border-green-400"> Introducing about us </span>
      </button>

      <div class="flex flex-col items-center rounded-lg bg-slate-200 gap-7">
        <span class="p-3 px-6 mx-auto font-semibold bg-white rounded-bl-lg rounded-br-lg"
          >Available for download:</span
        >

        <div
          class="grid items-center justify-around min-w-full gap-5 px-5 pb-5 lg:px-10 lg:grid-cols-2"
        >
          <button
            class="flex flex-col items-center justify-center gap-1 p-4 text-white duration-200 min-w-[15rem] rounded-2xl bg-slate-900 hover:bg-slate-950"
          >
            <div class="flex items-center gap-2 text-lg font-semibold">
              <box-icon type="logo" name="apple" color="white" />
              <span>App store</span>
            </div>
            <p class="text-sm opacity-50">For IOS & MacOS</p>
          </button>

          <button
            class="flex flex-col items-center justify-center gap-1 p-4 text-white duration-200 min-w-[15rem] rounded-2xl bg-slate-900 hover:bg-slate-950"
          >
            <div class="flex items-center gap-2 text-lg font-semibold">
              <box-icon type="logo" name="play-store" color="white" />
              <span>Play store</span>
            </div>
            <p class="text-sm opacity-50">For android > 6.0</p>
          </button>
        </div>
      </div>
    </div>

    <div class="flex flex-col gap-10 px-10 pb-10 lg:pb-0">
      <div class="mx-auto lg:mr-0">
        <p class="text-4xl font-bold">1.5M+</p>
        <p class="opacity-70">Happy users</p>
      </div>
      <img src="/header-mockup.svg" alt="header-mockup" draggable="false" />
    </div>
  </header>
</template>
