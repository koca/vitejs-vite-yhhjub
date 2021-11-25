<script setup lang="ts"></script>

<template>
  <div class="h-screen bg-gray-200">
    <div class="max-w-4xl mx-auto p-4 flex flex-col space-y-8">
      <h1 class="text-xl text-center">Google Tag Manager Tests</h1>
      <div class="example shadow-md bg-white p-4 rounded">
        <h2 class="mb-4">Test Account</h2>
        <div class="flex flex-wrap space-x-4">
          <c-button>trigger page_load event</c-button>
          <c-button>trigger click event</c-button>
        </div>
      </div>
      <div class="example shadow-md bg-white p-4 rounded">
        <h2 class="mb-4">MM Account</h2>
        <div class="flex flex-wrap space-x-4">todo</div>
      </div>
    </div>
  </div>
</template>
