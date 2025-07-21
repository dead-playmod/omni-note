<template>
  <header
    class="after:bg-border relative flex items-center justify-between px-8 py-6 after:absolute after:inset-x-8 after:bottom-0 after:h-px"
  >
    <UButton to="/" variant="ghost" class="group bg-transparent text-2xl">
      <span
        class="from-primary-700 to-primary bg-gradient-to-t bg-clip-text font-bold text-transparent transition-transform group-hover:-translate-y-1"
      >
        omni-note
      </span>
    </UButton>

    <UButton size="lg">Log in</UButton>
  </header>
</template>
