<template>
  <div class="max-w-3xl px-4 mx-auto">
    <header class="mt-8 mb-4 flex justify-between items-end">
      <div>
        <h1 class="text-2xl font-semibold">
          <NuxtLink to="/">Blog Terkini</NuxtLink>
        </h1>
        <p class="text-gray-500">Simpel Informasi Terpercaya</p>
      </div>

      <Btn></Btn>
    </header>
    
    <NuxtPage />
  </div>
</template>

<style>
body {
  @apply bg-gray-100 text-sm;
}
</style>
