<script lang="ts">
import Layout from '$components/layout/reservation/Layout.svelte';
</script>

<form action="/reservation/completion">
  <Layout>
    <main class="flex flex-1 flex-col items-center overflow-y-scroll">
      <div class="flex flex-col gap-2 max-w-lg w-1/4">
        <h1
          class="
            pt-8
            text-center text-2xl
            md:text-3xl
            font-medium
            text-gray-800
          ">
          予約編集
        </h1>

        <label for="employee_name" class="pl-1 text-gray-500">お客様氏名</label>
        <input
          id="employee_name"
          type="text"
          name="EMPLOYEE_NAME"
          value="春 たろう"
          class="input input-info input-bordered" />

        <label for="employee_name" class="pl-1 text-gray-500">部屋番号</label>
        <select name="" id="" class="select select-info">
          <option value="">選択してください</option>
          <option value="" selected>101</option>
          <option value="">102</option>
          <option value="">103</option>
          <option value="">104</option>
          <option value="">105</option>
          <option value="">201</option>
          <option value="">202</option>
          <option value="">203</option>
          <option value="">204</option>
          <option value="">205</option>
          <option value="">301</option>
          <option value="">302</option>
          <option value="">303</option>
          <option value="">304</option>
          <option value="">305</option>
        </select>

        <label for="employee_gender" class="pl-1 text-gray-500">利用人数</label>
        <select name="" id="" class="select select-info">
          <option value="">選択してください</option>
          <option value="1">1</option>
          <option value="2">2</option>
          <option value="3" selected>3</option>
          <option value="4">4</option>
          <option value="5">5</option>
          <option value="6">6</option>
          <option value="7">7</option>
          <option value="8">8</option>
          <option value="9">9</option>
          <option value="10">10</option>
        </select>

        <label for="employee_gender" class="pl-1 text-gray-500">利用日時</label>
        <input
          id="employee_name"
          type="date"
          name="EMPLOYEE_NAME"
          value="2021-01-19"
          class="input input-info input-bordered" />

        <label for="employee_gender" class="pl-1 text-gray-500">利用時間</label>
        <select name="" id="" class="select select-info">
          <option value="">選択してください</option>
          <option value="1">30分</option>
          <option value="1" selected>1時間</option>
          <option value="1">1時間30分</option>
          <option value="1">2時間</option>
          <option value="1">2時間30分</option>
          <option value="1">3時間</option>
          <option value="1">3時間30分</option>
        </select>

        <button
          class="
            w-full
            mx-auto
            text-white
            bg-blue-400
            border-0
            py-3
            px-8
            mt-4
            focus:outline-none
            hover:bg-blue-500
            text-lg
            rounded-full
          ">
          保存
        </button>
      </div>
    </main></Layout>
</form>
