<script lang="ts">
	import Layout from '$components/layout/contact/Layout.svelte';
</script>

<Layout>
	<main class="flex flex-1 flex-col items-center overflow-y-scroll">
		<div class="flex-1 overflow-x-auto w-full pb-40">
			<table class="table w-full">
				<thead>
					<tr>
						<th>予約番号</th>
						<th>予約人数</th>
						<th>予約日時</th>
						<th />
					</tr>
				</thead>
				<tbody>
					<tr>
						<th>12</th>
						<th>2</th>
						<td>2021/12/01 10:00</td>
						<td class="text-center w-24">
							<form action="/SD/servlet/shift_edit" method="POST">
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
                  "
								>
									詳細
								</button>
							</form>
						</td>
					</tr>
					<tr>
						<th>13</th>
						<th>5</th>
						<td>2021/12/01 10:00</td>
						<td class="text-center w-24">
							<form action="/SD/servlet/shift_edit" method="POST">
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
                  "
								>
									詳細
								</button>
							</form>
						</td>
					</tr>
					<tr>
						<th>14</th>
						<th>3</th>
						<td>2021/12/01 10:00</td>
						<td class="text-center w-24" />
					</tr>
				</tbody>
			</table>
		</div>
	</main>
</Layout>
