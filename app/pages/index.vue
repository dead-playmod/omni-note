<template>
  <div
    class="after:from-primary-700/30 relative flex flex-1 items-center justify-center after:absolute after:inset-0 after:animate-[pulse_5s_cubic-bezier(0.4,0,0.6,1)_infinite] after:bg-gradient-to-t after:to-transparent"
  >
    <div class="z-10 mb-[10%] flex flex-col items-center gap-2">
      <h1 class="text-center text-4xl">
        Welcome to

        <span
          class="from-primary-700 to-primary bg-gradient-to-t bg-clip-text font-bold text-transparent"
        >
          omni-note
        </span>
      </h1>

      <p class="text-muted text-lg">Yet another note-taking app 📝</p>

      <UButton to="/notes" size="lg" class="mt-4">Get Started</UButton>
    </div>
  </div>
</template>
