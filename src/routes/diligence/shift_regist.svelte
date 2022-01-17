<script lang="ts">
	import Layout from '$components/layout/diligence/Layout.svelte';
</script>

<Layout>
	<main class="flex flex-1 flex-col items-center overflow-scroll">
		<div class="flex flex-col gap-2 w-2/3 max-w-lg">
			<h1
				class="
          pt-8
          text-center text-2xl
          md:text-3xl
          font-medium
          text-gray-800
        "
			>
				シフト登録
			</h1>

			<label for="employee_id" class="pl-1 text-gray-500">従業員氏名</label>
			<input type="text" value="" class="input input-info input-bordered w-full" />

			<input type="hidden" name="EMPLOYEE_ID" value="" />

			<label for="shift_join_ymd" class="pl-1 text-gray-500">出勤予定日</label>
			<input
				id="shift_join_ymd"
				type="date"
				name="SHIFT_JOIN_YMD"
				value=""
				class="input input-info input-bordered w-full"
			/>

			<label for="shift_join_hour" class="pl-1 text-gray-500">出勤予定時刻</label>
			<div class="flex items-center">
				<input
					id="shift_join_hour"
					type="number"
					name="SHIFT_JOIN_HOUR"
					value=""
					class="input input-info input-bordered w-full"
				/>
				<label for="shift_join_hour" class="px-2 text-gray-500">時</label>

				<input
					id="shift_join_minute"
					type="number"
					name="SHIFT_JOIN_MINUTE"
					value=""
					class="input input-info input-bordered w-full"
				/>
				<label for="shift_join_minute" class="px-2 text-gray-500">分</label>
			</div>

			<label for="shift_leaving_hour" class="pl-1 text-gray-500">退勤予定時刻</label>
			<div class="flex items-center">
				<input
					id="shift_leaving_hour"
					type="number"
					name="SHIFT_LEAVING_HOUR"
					value=""
					class="input input-info input-bordered w-full"
				/>
				<label for="shift_leaving_hour" class="px-2 text-gray-500">時</label>

				<input
					id="shift_leaving_minute"
					type="number"
					name="SHIFT_LEAVING_MINUTE"
					value=""
					class="input input-info input-bordered w-full"
				/>
				<label for="shift_leaving_minute" class="px-2 text-gray-500">分</label>
			</div>

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
        "
			>
				送信
			</button>
		</div>
	</main>
</Layout>
