<script setup lang="ts"></script>

<template>
  <div class="w-76">
    <h1 class="text-3xl font-bold">Tell us about yourself</h1>
    <div class="flex flex-col justify-center items-center">
      <div class="flex-col mt-5 text-left">
        <div>
          <label for="detail-name" class="block text-md mb-2">Name</label>
          <input
            id="detail-name"
            type="text"
            name="name"
            class="border border-gray-600 p-1 rounded-sm"
          />
        </div>
        <div class="mt-5">
          <label for="detail-age" class="block text-md mb-2">Age</label>
          <input
            id="detail-age"
            type="number"
            name="age"
            class="border border-gray-600 p-1 rounded-sm"
          />
        </div>
        <div class="mt-5">
          <label for="detail-country" class="block text-md mb-2"
            >Where do you live</label
          >
          <select
            id="detail-country"
            class="border border-gray-600 p-1 w-full rounded-sm"
          >
            <option>Hong Kong</option>
            <option>USA</option>
            <option>Australia</option>
          </select>
        </div>
        <div class="mt-7">
          <div class="flex flex-col text-left mt-3">
            <label>
              <input type="radio" />
              <span class="ml-2 text-md">Standard</span>
            </label>
            <label>
              <input type="radio" />
              <span class="ml-2 text-md">Safe</span>
            </label>
            <label>
              <input type="radio" />
              <span class="ml-2 text-md">Super Safe</span>
            </label>
          </div>
        </div>
      </div>
      <div class="flex-col mt-6 h-8">
        <h2 class="text-large font-bold leading-snug">Your preminum is:</h2>
      </div>
    </div>
    <div class="flex mt-7 flex justify-around">
      <button name="back" class="btn-secondary">Back</button>
      <button name="next" class="btn-primary">Next</button>
    </div>
  </div>
</template>
