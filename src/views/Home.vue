<script>
import Button from "../components/Button.vue";
export default {
  components: {
    Button,
  },
};
</script>

<template>
  <div>
    <div class="mx-auto max-w-screen-xl px-4 py-12 sm:px-6 lg:flex lg:items-center lg:justify-between lg:py-16 lg:px-8">
      <h2 class="text-3xl font-extrabold leading-9 tracking-tight text-slate-700 sm:text-4xl sm:leading-10">
        Home Page
        <br />
        <br />
        <span class="text-cyan-500">Vite + Vue 3 + Tailwind CSS</span>
      </h2>
      <div class="mt-8 flex lg:mt-0 lg:flex-shrink-0">
        <div class="inline-flex rounded-md shadow">
          <router-link
            to="/about"
            class="inline-flex items-center justify-center rounded-md border border-transparent bg-cyan-500 px-5 py-3 text-base font-medium leading-6 text-white transition duration-150 ease-in-out hover:bg-cyan-600 focus:outline-none"
            >Next Page</router-link
          >
        </div>
        <Button />
      </div>
    </div>
  </div>
</template>
