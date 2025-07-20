<template>
  <div
    class="flex-1 flex items-center justify-center relative after:absolute after:inset-0 after:animate-[pulse_5s_cubic-bezier(0.4,0,0.6,1)_infinite] after:from-primary-700/30 after:to-transparent after:bg-gradient-to-t"
  >
    <div class="mb-[10%] z-10 flex flex-col items-center gap-2">
      <h1 class="text-4xl text-center">
        Welcome to

        <span
          class="from-primary-700 to-primary bg-gradient-to-t text-transparent font-bold bg-clip-text"
        >
          omni-note
        </span>
      </h1>

      <p class="text-muted text-lg">Yet another note-taking app 📝</p>

      <UButton to="/notes" size="lg" class="mt-4">Get Started</UButton>
    </div>
  </div>
</template>
