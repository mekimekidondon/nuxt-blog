<template>
    <footer class="flex flex-col text-sm text-gray-800 font-quicksand">
      <ul class="flex flex-col mb-3 justify-center space-y-2 sm:space-y-0 sm:space-x-5 sm:flex-row">
        <li>
          <NuxtLink to="/about" class="transition-colors duration-300 rounded px-2 py-1 hover:bg-gray-400">About</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/profile" class="transition-colors duration-300 rounded px-2 py-1 hover:bg-gray-400">Profile</NuxtLink>
        </li>
      </ul>
      <p class="text-center mt-3">
        © 2023
      </p>
    </footer>
  </template>

<style>
.nuxt-content * {
  margin-top: 15px;
  margin-bottom: 15px;
}
.nuxt-content h1 {
  font-size: 1.5rem;
}
.nuxt-content h2 {
  font-size: 1.25rem;
}
.nuxt-content a {
  color: blue;
}
</style>