<template>
  <button class="button">I use scoped Tailwind classes</button>
</template>

<style lang="postcss" scoped>
.button {
  @apply border border-green-500 bg-green-500 text-white rounded-md px-4 py-2 m-2;
}
</style>
