<script lang="ts">
import Navigate from '$components/layout/contact/Navigate.svelte';
</script>

<div class="flex flex-col w-full h-screen">
  <header class="w-full bg-amber-400 py-4 border-b border-gray-200">
    <h1 class="text-2xl pl-8 font-bold text-white">予約管理</h1>
  </header>

  <div class="flex flex-1 w-full bg-gray-100">
    <Navigate />
    <slot />
  </div>
</div>
