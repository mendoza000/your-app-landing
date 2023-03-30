<script setup lang="ts">
import 'boxicons'
</script>

<template>
  <div class="grid gap-10 px-10 py-20 bg-slate-50 lg:grid-cols-2">
    <div class="flex flex-col gap-14">
      <p class="text-4xl font-semibold">Payment plans made easier together</p>
      <div class="flex items-center gap-20">
        <div>
          <p class="text-3xl font-bold text-center text-green-600">2.3M+</p>
          <span class="opacity-60">Downloaded</span>
        </div>

        <div>
          <p class="text-3xl font-bold text-center text-green-600">4.9</p>
          <span class="opacity-60">Ratings</span>
        </div>
      </div>
    </div>

    <div>
      <div class="flex flex-col gap-5 border-b-2 pb-7 border-slate-200">
        <div class="flex items-center gap-2 text-xl font-semibold">
          <div class="flex items-center p-2 rounded-lg bg-slate-900">
            <box-icon name="target-lock" color="white" />
          </div>
          <span>Clear targets</span>
        </div>

        <p class="opacity-70">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque nulla quam voluptatum
          earum cupiditate quis sed accusamus saepe commodi corrupti!
        </p>
      </div>

      <div class="flex flex-col gap-5 pt-7">
        <div class="flex items-center gap-2 text-xl font-semibold">
          <div class="flex items-center p-2 rounded-lg bg-slate-900">
            <box-icon name="stats" color="white" />
          </div>
          <span>Promising progress</span>
        </div>

        <p class="opacity-70">
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Facere eveniet laborum iste
          nobis cum soluta illum eligendi saepe dolores quam.
        </p>
      </div>
    </div>
  </div>
</template>
