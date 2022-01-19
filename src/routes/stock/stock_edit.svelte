<script lang="ts">
import Layout from '$components/layout/stock/Layout.svelte';
</script>

<form action="/stock/completion">
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
          商品編集
        </h1>

        <label for="employee_name" class="pl-1 text-gray-500">商品名</label>
        <input
          id="employee_name"
          type="text"
          name="EMPLOYEE_NAME"
          value="商品A
        "
          class="input input-info input-bordered" />

        <label for="employee_name" class="pl-1 text-gray-500">入荷数</label>
        <input
          id="employee_name"
          type="number"
          name="EMPLOYEE_NAME"
          value="100"
          class="input input-info input-bordered" />

        <label for="employee_gender" class="pl-1 text-gray-500">入荷日</label>
        <input
          id="employee_name"
          type="date"
          name="EMPLOYEE_NAME"
          value="2021-01-19"
          class="input input-info input-bordered" />

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
          登録
        </button>
      </div>
    </main>
  </Layout>
</form>
