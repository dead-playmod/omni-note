<template>
  <header
    class="px-8 py-6 flex justify-between items-center relative after:absolute after:inset-x-8 after:bottom-0 after:h-px after:bg-border"
  >
    <UButton to="/" variant="ghost" class="group text-2xl bg-transparent">
      <span
        class="from-primary-700 to-primary bg-gradient-to-t text-transparent font-bold bg-clip-text transition-transform group-hover:-translate-y-1"
      >
        omni-note
      </span>
    </UButton>

    <UButton size="lg">Log in</UButton>
  </header>
</template>
