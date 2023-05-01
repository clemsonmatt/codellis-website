<template>
  <router-view />
</template>

<style>
@font-face {
  font-family: 'CapitalPoster';
  src: url('~@/assets/fonts/Capital-Poster.ttf') format('truetype');
}
@font-face {
  font-family: 'AlbertSans';
  src: url('~@/assets/fonts/AlbertSans-Regular.ttf') format('truetype');
}

#app {
  font-family: AlbertSans, Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #0e4168;
  background-color: #ffffff;
  /* color: #101b30; */
}

.hero {
  @apply uppercase text-7xl md:text-8xl lg:text-9xl font-['CapitalPoster'];
}
.section {
  @apply uppercase text-6xl md:text-7xl lg:text-8xl font-['CapitalPoster'];
}
.bg-dark {
  background-color: #0e4168;
  /* background-color: #101b30; */
}
.btn-custom {
  @apply bg-slate-200 py-5 px-10 rounded-full uppercase shadow-xl font-semibold;
}
.card {
  @apply p-10 shadow-2xl rounded-2xl bg-white mx-4 md:mx-0;
}
</style>
