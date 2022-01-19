<script lang="ts">
import Layout from '$components/layout/stock/Layout.svelte';
</script>

<Layout>
  <main class="flex flex-1 flex-col items-center overflow-y-scroll">
    <div class="flex-1 overflow-x-auto w-full pb-40">
      <table class="table w-full">
        <thead>
          <tr>
            <th>商品名</th>
            <th>商品名在庫数</th>
            <th>入荷日</th>
            <th>入荷予定日</th>
            <th></th>
          </tr>
        </thead>

        <tbody>
          <tr>
            <th>食品A</th>
            <th>100</th>
            <td>2021/12/01 10:00</td>
            <td>2021/12/01 15:00</td>
            <td class="text-center w-24">
              <form action="/stock/stock_edit" method="POST">
                <input type="hidden" name="SHIFT_ID" value="" />
                <button
                  class="
                    text-white
                    bg-gray-400
                    border-0
                    py-1
                    px-4
                    focus:outline-none
                    hover:bg-gray-400
                    rounded-full
                  ">
                  編集
                </button>
              </form>
            </td>
          </tr>
          <tr>
            <th>食品B</th>
            <th>100</th>
            <td>2021/12/01 10:00</td>
            <td>2021/12/01 15:00</td>
            <td class="text-center w-24">
              <form action="/stock/stock_edit" method="POST">
                <input type="hidden" name="SHIFT_ID" value="" />
                <button
                  class="
                    text-white
                    bg-gray-400
                    border-0
                    py-1
                    px-4
                    focus:outline-none
                    hover:bg-gray-400
                    rounded-full
                  ">
                  編集
                </button>
              </form>
            </td>
          </tr>
        </tbody>
      </table>
    </div>
  </main>
</Layout>
