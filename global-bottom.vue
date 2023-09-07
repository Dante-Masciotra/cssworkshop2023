<template>
    <footer
      v-if="$slidev.nav.currentLayout !== 'cover'"
      class="absolute bottom-0 right-0 p-2 text-white font-bold"
    >
      {{ $slidev.nav.currentPage }}/{{ $slidev.nav.total }}
    </footer>
  </template>
  