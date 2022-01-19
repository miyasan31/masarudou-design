<script lang="ts">
import Layout from '$components/layout/order/Layout.svelte';
</script>

<div class="flex w-full">
  <div class="container px-5 mx-auto h-screen">
    <h1 class="py-4 text-lg font-bold">フードメニュー</h1>
    <div class="flex flex-wrap -m-2">
      <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
        <div class="h-full flex items-center border-gray-200 border p-4 rounded-lg">
          <img
            alt="team"
            class="w-20 h-20 bg-gray-100 object-cover object-center flex-shrink-0 rounded mr-4"
            src="https://dummyimage.com/80x80" />
          <div class="flex-grow">
            <h2 class="text-gray-900 title-font font-medium">ご飯</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
      <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
        <div class="h-full flex items-center border-gray-200 border p-4 rounded-lg">
          <img
            alt="team"
            class="w-20 h-20 bg-gray-100 object-cover object-center flex-shrink-0 rounded mr-4"
            src="https://dummyimage.com/84x84" />
          <div class="flex-grow">
            <h2 class="text-gray-900 title-font font-medium">焼肉</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
      <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
        <div class="h-full flex items-center border-gray-200 border p-4 rounded-lg">
          <img
            alt="team"
            class="w-20 h-20 bg-gray-100 object-cover object-center flex-shrink-0 rounded mr-4"
            src="https://dummyimage.com/88x88" />
          <div class="flex-grow">
            <h2 class="text-gray-900 title-font font-medium">天ぷら</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
      <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
        <div class="h-full flex items-center border-gray-200 border p-4 rounded-lg">
          <img
            alt="team"
            class="w-20 h-20 bg-gray-100 object-cover object-center flex-shrink-0 rounded mr-4"
            src="https://dummyimage.com/90x90" />
          <div class="flex-grow">
            <h2 class="text-gray-900 title-font font-medium">餃子</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
      <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
        <div class="h-full flex items-center border-gray-200 border p-4 rounded-lg">
          <img
            alt="team"
            class="w-20 h-20 bg-gray-100 object-cover object-center flex-shrink-0 rounded mr-4"
            src="https://dummyimage.com/94x94" />
          <div class="flex-grow">
            <h2 class="text-gray-900 title-font font-medium">ラーメン</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
      <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
        <div class="h-full flex items-center border-gray-200 border p-4 rounded-lg">
          <img
            alt="team"
            class="w-20 h-20 bg-gray-100 object-cover object-center flex-shrink-0 rounded mr-4"
            src="https://dummyimage.com/98x98" />
          <div class="flex-grow">
            <h2 class="text-gray-900 title-font font-medium">かまぼこ</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
      <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
        <div class="h-full flex items-center border-gray-200 border p-4 rounded-lg">
          <img
            alt="team"
            class="w-20 h-20 bg-gray-100 object-cover object-center flex-shrink-0 rounded mr-4"
            src="https://dummyimage.com/100x90" />
          <div class="flex-grow">
            <h2 class="text-gray-900 title-font font-medium">なんちゃらパスタ</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
      <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
        <div class="h-full flex items-center border-gray-200 border p-4 rounded-lg">
          <img
            alt="team"
            class="w-20 h-20 bg-gray-100 object-cover object-center flex-shrink-0 rounded mr-4"
            src="https://dummyimage.com/104x94" />
          <div class="flex-grow">
            <h2 class="text-gray-900 title-font font-medium">ポテト</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
      <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
        <div class="h-full flex items-center border-gray-200 border p-4 rounded-lg">
          <img
            alt="team"
            class="w-20 h-20 bg-gray-100 object-cover object-center flex-shrink-0 rounded mr-4"
            src="https://dummyimage.com/108x98" />
          <div class="flex-grow">
            <h2 class="text-gray-900 title-font font-medium">まさる堂気まぐれメニュー</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
    </div>
    <!-- ----------------------------------------------------------------------- -->
    <h1 class="py-4 text-lg font-bold">ドリンクメニュー</h1>
    <div class="flex flex-wrap -m-2">
      <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
        <div class="h-full flex items-center border-gray-200 border p-4 rounded-lg">
          <img
            alt="team"
            class="w-20 h-20 bg-gray-100 object-cover object-center flex-shrink-0 rounded mr-4"
            src="https://dummyimage.com/80x80" />
          <div class="flex-grow">
            <h2 class="text-gray-900 title-font font-medium">コーラ</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
      <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
        <div class="h-full flex items-center border-gray-200 border p-4 rounded-lg">
          <img
            alt="team"
            class="w-20 h-20 bg-gray-100 object-cover object-center flex-shrink-0 rounded mr-4"
            src="https://dummyimage.com/84x84" />
          <div class="flex-grow">
            <h2 class="text-gray-900 title-font font-medium">ビール</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
      <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
        <div class="h-full flex items-center border-gray-200 border p-4 rounded-lg">
          <img
            alt="team"
            class="w-20 h-20 bg-gray-100 object-cover object-center flex-shrink-0 rounded mr-4"
            src="https://dummyimage.com/88x88" />
          <div class="flex-grow">
            <h2 class="text-gray-900 title-font font-medium">焼酎</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
      <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
        <div class="h-full flex items-center border-gray-200 border p-4 rounded-lg">
          <img
            alt="team"
            class="w-20 h-20 bg-gray-100 object-cover object-center flex-shrink-0 rounded mr-4"
            src="https://dummyimage.com/90x90" />
          <div class="flex-grow">
            <h2 class="text-gray-900 title-font font-medium">カクテル</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
      <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
        <div class="h-full flex items-center border-gray-200 border p-4 rounded-lg">
          <img
            alt="team"
            class="w-20 h-20 bg-gray-100 object-cover object-center flex-shrink-0 rounded mr-4"
            src="https://dummyimage.com/94x94" />
          <div class="flex-grow">
            <h2 class="text-gray-900 title-font font-medium">梅酒</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
      <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
        <div class="h-full flex items-center border-gray-200 border p-4 rounded-lg">
          <img
            alt="team"
            class="w-20 h-20 bg-gray-100 object-cover object-center flex-shrink-0 rounded mr-4"
            src="https://dummyimage.com/98x98" />
          <div class="flex-grow">
            <h2 class="text-gray-900 title-font font-medium">カルピス</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="flex flex-col p-4 w-1/4 bg-white h-screen border-l border-l-gray-200">
    <div>
      <ul>
        <li class="flex items-center justify-between p-2 font-bold border-b border-gray-200">
          <div>ラーメン</div>
          <div>300円</div>
        </li>

        <li class="flex items-center justify-between p-2 font-bold border-b border-gray-200">
          <div>焼肉</div>
          <div>300円</div>
        </li>

        <li class="flex items-center justify-between p-2 font-bold border-b border-gray-200">
          <div>焼酎</div>
          <div>300円</div>
        </li>
      </ul>
    </div>
    <div class="flex-grow"></div>
    <div class="font-bold text-xl py-4">合計金額: 900円</div>
    <a href="/order/order_done" class="btn btn-info">注文する</a>
  </div>
</div>
