<div class="flex flex-col w-full h-screen">
  <div class="flex flex-col w-full">
    <header class="flex items-center justify-between w-full bg-blue-400 py-4 px-4 border-b border-gray-200">
      <h1 class="text-2xl pl-8 font-bold text-white">予約管理</h1>
      <a href="/reservation/reservation_register" class="btn btn-info">予約登録</a>
    </header>
  </div>

  <div class="flex flex-1 w-full bg-gray-100">
    <slot />
  </div>
</div>
