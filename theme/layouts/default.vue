<template>
  <div class="slidev-layout" :class="{ grid: $attrs.center }">
    <CornerCurves
      class="absolute right-1 transform scale-x--100 rotate-265 scale-60"
      style="top: -5rem"
    />
    <div class="my-auto z-10 relative">
      <slot />
    </div>
  </div>
</template>
