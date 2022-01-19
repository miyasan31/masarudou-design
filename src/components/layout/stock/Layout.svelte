<div class="flex flex-col w-full h-screen">
  <div class="flex flex-col w-full">
    <header class="flex items-center justify-between w-full bg-blue-400 py-4 px-4 border-b border-gray-200">
      <h1 class="text-2xl pl-8 font-bold text-white">在庫管理</h1>
      <a href="/stock/stock_register" class="btn btn-info">商品登録</a>
    </header>
  </div>

  <div class="flex flex-1 w-full bg-gray-100">
    <slot />
  </div>
</div>
