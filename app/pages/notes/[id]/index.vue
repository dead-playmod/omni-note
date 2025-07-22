<template>
  <div class="flex flex-col h-full">
    <div
      class="h-(--ui-header-height) border-b border-default shrink-0 flex items-center gap-1.5 px-4"
    >
      <p>Note {{ $route.params.id }}</p>

      <UButton to="/notes" variant="ghost" icon="i-lucide-x" class="ml-auto" />
    </div>

    <textarea
      class="py-6 px-4 w-full h-full resize-none"
      placeholder="Start typing here..."
    />
  </div>
</template>
