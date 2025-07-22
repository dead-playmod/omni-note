<script setup lang="ts">
import type { PageLink } from '@nuxt/ui-pro';

const links = ref<PageLink[]>([
  {
    label: 'New Note',
    icon: 'i-lucide-plus',
    to: '/notes/new',
  },
  ...Array.from({ length: 100 }, (_, i) => ({
    label: `Link ${i + 1}`,
    icon: 'i-lucide-file-text',
    to: `/notes/${i + 1}`,
  })),
]);
</script>

<template>
  <div>
    <LayoutHeader />

    <UDashboardGroup class="mt-26">
      <template #header>
        <LayoutHeader />
      </template>

      <UDashboardSidebar resizable class="pb-26">
        <template #header> Notes </template>

        <UPageLinks :links />
      </UDashboardSidebar>

      <main class="flex-1 flex flex-col">
        <slot />
      </main>
    </UDashboardGroup>
  </div>
</template>
