<script lang="ts">
import Layout from '$components/layout/diligence/Layout.svelte';
</script>

<Layout>
  <main class="flex flex-1 flex-col items-center overflow-y-scroll">
    <div class="flex-1 overflow-x-auto w-full pb-40">
      <table class="table w-full">
        <thead>
          <tr>
            <th>従業員氏名</th>
            <th>従業員氏名（フリガナ）</th>
            <th>生年月日</th>
            <th>性別</th>
            <th>電話番号</th>
            <th>メールアドレス</th>
            <th>従業員タイプ</th>
            <th>入社年月日</th>
            <th></th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th>春野 春子</th>
            <td>はるの はるこ</td>
            <td>2000/12/01</td>
            <td>男</td>
            <td>080-1929-3943</td>
            <td>example@gmail.com</td>
            <td>店長</td>
            <td>2021/12/01</td>
            <td class="text-center w-24 px-1">
              <form action="/SD/servlet/employee_edit" method="POST">
                <input type="hidden" name="EMPLOYEE_ID" value="" />
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
                  "
                >
                  編集
                </button>
              </form>
            </td>
          </tr>
          <tr>
            <th>春野 春子</th>
            <td>はるの はるこ</td>
            <td>2000/12/01</td>
            <td>男</td>
            <td>080-1929-3943</td>
            <td>example@gmail.com</td>
            <td>正社員</td>
            <td>2021/12/01</td>
            <td class="text-center w-24 px-1">
              <form action="/SD/servlet/employee_edit" method="POST">
                <input type="hidden" name="EMPLOYEE_ID" value="" />
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
                  "
                >
                  編集
                </button>
              </form>
            </td>
          </tr>
          <tr>
            <th>春野 春子</th>
            <td>はるの はるこ</td>
            <td>2000/12/01</td>
            <td>女</td>
            <td>080-1929-3943</td>
            <td>example@gmail.com</td>
            <td>アルバイト</td>
            <td>2021/12/01</td>
            <td class="text-center w-24 px-1"></td>
          </tr>
        </tbody>
      </table>
    </div>
  </main>
</Layout>
