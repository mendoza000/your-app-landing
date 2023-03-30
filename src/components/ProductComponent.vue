<script setup lang="ts">
import 'boxicons'
</script>

<template>
  <div class="flex flex-col gap-10 px-10 py-20 bg-slate-50">
    <div class="flex flex-col min-w-full gap-5 px-10 bg-slate-900 rounded-tr-xl rounded-tl-xl">
      <div class="flex px-10 py-3 mx-auto bg-white rounded-br-xl rounded-bl-xl">
        <span class="text-green-600"> Monitor easily </span>
      </div>

      <div class="grid items-center gap-10 pt-5 pb-10 text-white lg:grid-cols-2">
        <div class="flex flex-col gap-5">
          <h3 class="text-3xl font-semibold">
            Connecting your beliefs with discourse with friends
          </h3>
          <p class="opacity-70">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quam, perferendis!
          </p>
          <button
            class="max-w-xs py-3 mt-5 font-semibold duration-200 bg-green-400 text-slate-900 rounded-xl hover:bg-green-600"
          >
            Learn more
          </button>
        </div>

        <img src="/project.svg" alt="project-svg" class="mx-auto lg:ml-auto h-5/6" />
      </div>
    </div>

    <div class="grid gap-10 lg:grid-cols-2">
      <div class="flex flex-col gap-5 px-10 py-10 bg-slate-200 rounded-br-xl rounded-bl-xl">
        <div class="flex flex-col items-start gap-2 text-2xl font-semibold">
          <div class="flex items-center p-2 rounded-lg bg-slate-900">
            <box-icon name="shield" color="white" class="w-10 h-10" />
          </div>
          <span>Security and compilance</span>
        </div>

        <p class="opacity-70">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. A, labore.
        </p>

        <button
          class="text-green-600 border-b-2 border-green-500 max-w-[7rem] font-semibold text-left"
        >
          Learn more...
        </button>
      </div>

      <div class="flex flex-col gap-5 px-10 py-10 bg-slate-200 rounded-br-xl rounded-bl-xl">
        <div class="flex flex-col items-start gap-2 text-2xl font-semibold">
          <div class="flex items-center p-2 rounded-lg bg-slate-900">
            <box-icon type="solid" name="dashboard" color="white" class="w-10 h-10" />
          </div>
          <span>Integrations</span>
        </div>

        <p class="opacity-70">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam, saepe?
        </p>

        <button
          class="text-green-600 border-b-2 border-green-500 max-w-[7rem] font-semibold text-left"
        >
          Learn more...
        </button>
      </div>
    </div>
  </div>
</template>
