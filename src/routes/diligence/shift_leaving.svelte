<script lang="ts">
	import Layout from '$components/layout/diligence/Layout.svelte';
</script>

<Layout>
	<main class="flex flex-1 flex-col items-center overflow-scroll">
		<div class="flex flex-col gap-2 w-2/3 max-w-sm">
			<h1
				class="
          pt-8
          text-center text-2xl
          md:text-3xl
          font-medium
          text-gray-800
        "
			>
				退勤登録
			</h1>

			<label for="employee_id" class="pl-1 text-gray-500">従業員氏名</label>
			<input type="text" value="春 太郎" class="input input-info input-bordered w-full" />

			<input type="hidden" name="ATTENDANCE_ID" value="" />

			<button
				class="
          w-full
          mx-auto
          text-white
          bg-blue-400
          border-0
          py-3
          px-8
          mt-2
          focus:outline-none
          hover:bg-blue-500
          text-lg
          rounded-full
        "
			>
				退勤
			</button>
		</div>
	</main>
</Layout>
