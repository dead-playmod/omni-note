<template>
  <div
    class="h-(--ui-header-height) border-b border-default shrink-0 flex items-center gap-1.5 px-4"
  >
    <UInput
      name="Note name"
      placeholder="Type in note name here..."
      class="w-full"
    />

    <UButton variant="ghost" color="success" icon="i-lucide-check" />
    <UButton to="/notes" variant="ghost" icon="i-lucide-x" />
  </div>
</template>
