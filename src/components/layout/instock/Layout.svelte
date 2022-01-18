<script lang="ts">
import Navigate from '$components/layout/instock/Navigate.svelte';
</script>

<div class="flex flex-col w-full h-screen">
  <header class="w-full bg-teal-400 py-4 border-b border-gray-200">
    <h1 class="text-2xl pl-8 font-bold text-white">在庫管理システム</h1>
  </header>

  <div class="flex flex-1 w-full bg-gray-100">
    <Navigate />
    <slot />
  </div>
</div>
