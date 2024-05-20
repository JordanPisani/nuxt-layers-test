<template>
  <h1>Extending Components is Fun!</h1>
  <button href="#">test button</button>

  <UCard>
    <template #header>
      <Placeholder class="h-8" />
    </template>

    <Placeholder class="h-32" />

    <template #footer>
      <Placeholder class="h-8" />
    </template>
  </UCard>
</template>
