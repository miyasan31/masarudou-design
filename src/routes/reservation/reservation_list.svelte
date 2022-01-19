<script lang="ts">
import Layout from '$components/layout/reservation/Layout.svelte';
</script>

<Layout>
  <main class="flex flex-1 flex-col items-center overflow-y-scroll">
    <div class="flex-1 overflow-x-auto w-full pb-40">
      <table class="table w-full">
        <thead>
          <tr>
            <th>お客様氏名</th>
            <th>部屋番号</th>
            <th>利用人数</th>
            <th>利用日時</th>
            <th>利用時間</th>
            <th></th>
          </tr>
        </thead>

        <tbody>
          <tr>
            <th>春 たろう</th>
            <th>101</th>
            <td>3</td>
            <td>2021/01/19 10:30</td>
            <td>1時間</td>
            <td class="text-center w-24">
              <form action="/reservation/reservation_edit" method="POST">
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
            <th>春 はな子</th>
            <th>201</th>
            <td>10</td>
            <td>2021/01/19 10:30</td>
            <td>2時間</td>
            <td class="text-center w-24">
              <form action="/reservation/reservation_edit" method="POST">
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
