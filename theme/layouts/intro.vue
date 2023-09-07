<template>
  <div class="slidev-layout intro grid">
    <LayoutHeader />
    <CornerCurves
      class="absolute left-2 transform rotate-100"
      style="top: -5rem;"
    />
    <div class="flex flex-col justify-center text-center">
      <slot />
    </div>
  </div>
</template>

<style>
.slidev-layout.intro {
  h1 {
    @apply text-6xl leading-20 font-extrabold text-primary;
  }

  h1 + p {
    @apply opacity-60 -mt-4 text-2xl;
  }

  a {
    @apply text-white hover:text-gray-200;
  }
}
</style>
