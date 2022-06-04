<template>
  <div>
    <header class="bg-slate-200 shadow-lg shadow-blur-xl shadow-cyan-500 font-display" v-if="$route.meta.title">
      <div class="mx-auto max-w-7xl px-4 py-6 sm:px-6 lg:px-8 ">
        <h1 class="text-3xl font-bold leading-tight text-slate-600">{{ $route.meta.title }}</h1>
      </div>
    </header>
    <main>
      <router-view />
    </main>
  </div>
</template>
