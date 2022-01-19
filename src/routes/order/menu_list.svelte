<script lang="ts">
import Layout from '$components/layout/order/Layout.svelte';
</script>

<div class="flex w-full">
  <div class="container h-screen px-5 mx-auto overflow-y-auto">
    <h1 class="py-4 text-lg font-bold">フードメニュー</h1>
    <div class="flex flex-wrap -m-2">
      <div class="w-full p-2 lg:w-1/3 md:w-1/2">
        <div class="flex items-center h-full p-4 border border-gray-200 rounded-lg">
          <img
            alt="team"
            class="flex-shrink-0 object-cover object-center w-20 h-20 mr-4 bg-gray-100 rounded"
            src="https://dummyimage.com/80x80" />
          <div class="flex-grow">
            <h2 class="font-medium text-gray-900 title-font">ご飯</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
      <div class="w-full p-2 lg:w-1/3 md:w-1/2">
        <div class="flex items-center h-full p-4 border border-gray-200 rounded-lg">
          <img
            alt="team"
            class="flex-shrink-0 object-cover object-center w-20 h-20 mr-4 bg-gray-100 rounded"
            src="https://dummyimage.com/84x84" />
          <div class="flex-grow">
            <h2 class="font-medium text-gray-900 title-font">焼肉</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
      <div class="w-full p-2 lg:w-1/3 md:w-1/2">
        <div class="flex items-center h-full p-4 border border-gray-200 rounded-lg">
          <img
            alt="team"
            class="flex-shrink-0 object-cover object-center w-20 h-20 mr-4 bg-gray-100 rounded"
            src="https://dummyimage.com/88x88" />
          <div class="flex-grow">
            <h2 class="font-medium text-gray-900 title-font">天ぷら</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
      <div class="w-full p-2 lg:w-1/3 md:w-1/2">
        <div class="flex items-center h-full p-4 border border-gray-200 rounded-lg">
          <img
            alt="team"
            class="flex-shrink-0 object-cover object-center w-20 h-20 mr-4 bg-gray-100 rounded"
            src="https://dummyimage.com/90x90" />
          <div class="flex-grow">
            <h2 class="font-medium text-gray-900 title-font">餃子</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
      <div class="w-full p-2 lg:w-1/3 md:w-1/2">
        <div class="flex items-center h-full p-4 border border-gray-200 rounded-lg">
          <img
            alt="team"
            class="flex-shrink-0 object-cover object-center w-20 h-20 mr-4 bg-gray-100 rounded"
            src="https://dummyimage.com/94x94" />
          <div class="flex-grow">
            <h2 class="font-medium text-gray-900 title-font">ラーメン</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
      <div class="w-full p-2 lg:w-1/3 md:w-1/2">
        <div class="flex items-center h-full p-4 border border-gray-200 rounded-lg">
          <img
            alt="team"
            class="flex-shrink-0 object-cover object-center w-20 h-20 mr-4 bg-gray-100 rounded"
            src="https://dummyimage.com/98x98" />
          <div class="flex-grow">
            <h2 class="font-medium text-gray-900 title-font">かまぼこ</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
      <div class="w-full p-2 lg:w-1/3 md:w-1/2">
        <div class="flex items-center h-full p-4 border border-gray-200 rounded-lg">
          <img
            alt="team"
            class="flex-shrink-0 object-cover object-center w-20 h-20 mr-4 bg-gray-100 rounded"
            src="https://dummyimage.com/100x90" />
          <div class="flex-grow">
            <h2 class="font-medium text-gray-900 title-font">なんちゃらパスタ</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
      <div class="w-full p-2 lg:w-1/3 md:w-1/2">
        <div class="flex items-center h-full p-4 border border-gray-200 rounded-lg">
          <img
            alt="team"
            class="flex-shrink-0 object-cover object-center w-20 h-20 mr-4 bg-gray-100 rounded"
            src="https://dummyimage.com/104x94" />
          <div class="flex-grow">
            <h2 class="font-medium text-gray-900 title-font">ポテト</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
      <div class="w-full p-2 lg:w-1/3 md:w-1/2">
        <div class="flex items-center h-full p-4 border border-gray-200 rounded-lg">
          <img
            alt="team"
            class="flex-shrink-0 object-cover object-center w-20 h-20 mr-4 bg-gray-100 rounded"
            src="https://dummyimage.com/108x98" />
          <div class="flex-grow">
            <h2 class="font-medium text-gray-900 title-font">まさる堂気まぐれメニュー</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
    </div>
    <!-- ----------------------------------------------------------------------- -->
    <h1 class="py-4 text-lg font-bold">ドリンクメニュー</h1>
    <div class="flex flex-wrap -m-2">
      <div class="w-full p-2 lg:w-1/3 md:w-1/2">
        <div class="flex items-center h-full p-4 border border-gray-200 rounded-lg">
          <img
            alt="team"
            class="flex-shrink-0 object-cover object-center w-20 h-20 mr-4 bg-gray-100 rounded"
            src="https://dummyimage.com/80x80" />
          <div class="flex-grow">
            <h2 class="font-medium text-gray-900 title-font">コーラ</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
      <div class="w-full p-2 lg:w-1/3 md:w-1/2">
        <div class="flex items-center h-full p-4 border border-gray-200 rounded-lg">
          <img
            alt="team"
            class="flex-shrink-0 object-cover object-center w-20 h-20 mr-4 bg-gray-100 rounded"
            src="https://dummyimage.com/84x84" />
          <div class="flex-grow">
            <h2 class="font-medium text-gray-900 title-font">ビール</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
      <div class="w-full p-2 lg:w-1/3 md:w-1/2">
        <div class="flex items-center h-full p-4 border border-gray-200 rounded-lg">
          <img
            alt="team"
            class="flex-shrink-0 object-cover object-center w-20 h-20 mr-4 bg-gray-100 rounded"
            src="https://dummyimage.com/88x88" />
          <div class="flex-grow">
            <h2 class="font-medium text-gray-900 title-font">焼酎</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
      <div class="w-full p-2 lg:w-1/3 md:w-1/2">
        <div class="flex items-center h-full p-4 border border-gray-200 rounded-lg">
          <img
            alt="team"
            class="flex-shrink-0 object-cover object-center w-20 h-20 mr-4 bg-gray-100 rounded"
            src="https://dummyimage.com/90x90" />
          <div class="flex-grow">
            <h2 class="font-medium text-gray-900 title-font">カクテル</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
      <div class="w-full p-2 lg:w-1/3 md:w-1/2">
        <div class="flex items-center h-full p-4 border border-gray-200 rounded-lg">
          <img
            alt="team"
            class="flex-shrink-0 object-cover object-center w-20 h-20 mr-4 bg-gray-100 rounded"
            src="https://dummyimage.com/94x94" />
          <div class="flex-grow">
            <h2 class="font-medium text-gray-900 title-font">梅酒</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
      <div class="w-full p-2 lg:w-1/3 md:w-1/2">
        <div class="flex items-center h-full p-4 border border-gray-200 rounded-lg">
          <img
            alt="team"
            class="flex-shrink-0 object-cover object-center w-20 h-20 mr-4 bg-gray-100 rounded"
            src="https://dummyimage.com/98x98" />
          <div class="flex-grow">
            <h2 class="font-medium text-gray-900 title-font">カルピス</h2>
            <p class="text-gray-500">300円</p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="flex flex-col p-4 w-[400px] bg-white h-screen border-l border-l-gray-200">
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
    <div class="py-4 text-xl font-bold">合計金額: 900円</div>
    <a href="/order/order_done" class="btn btn-info">注文する</a>
  </div>
</div>
