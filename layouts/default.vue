<template>
  <div class="flex flex-col">
    <header
      class="
        p-4
        bg-black
        text-white
        sticky
        w-full
        top-0
        inline-flex
        justify-between
      "
    >
      <h1 class="my-auto font-mono font-semibold">Silvester wali</h1>
      <nav class="flex flex-row">
        <ul class="space-x-2 inline-flex">
          <li>
            <nuxt-link
              to="/"
              class="
                hover:bg-gray-500
                p-2
                rounded-lg
                hover:ring-2 hover:ring-gray-700
              "
              active-class="bg-gray-600"
              exact
              >Home</nuxt-link
            >
          </li>
          <li>
            <nuxt-link
              to="/container"
              class="
                hover:bg-gray-500
                p-2
                rounded-lg
                hover:ring-2 hover:ring-gray-700
              "
              active-class="bg-gray-600"
              exact
              >Container</nuxt-link
            >
          </li>
          <li>
            <nuxt-link
              to="/form"
              class="
                hover:bg-gray-500
                p-2
                rounded-lg
                hover:ring-2 hover:ring-gray-700
              "
              active-class="bg-gray-600"
              exact
              >form</nuxt-link
            >
          </li>
        </ul>
      </nav>
    </header>
    <main class="flex-1 static min-h-screen">
      <nuxt />
    </main>
    <footer class="p-4 bg-black text-white flex">
      <ul class="mx-auto">
        <li>
          <a class="inline-flex space-x-3">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              stroke-width="2"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M12 8v13m0-13V6a2 2 0 112 2h-2zm0 0V5.5A2.5 2.5 0 109.5 8H12zm-7 4h14M5 12a2 2 0 110-4h14a2 2 0 110 4M5 12v7a2 2 0 002 2h10a2 2 0 002-2v-7"
              />
            </svg>
            Get code
          </a>
        </li>
        <li>Lorem ipsum</li>
      </ul>
    </footer>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
</style>