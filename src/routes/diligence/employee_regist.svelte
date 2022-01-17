<script lang="ts">
	import Layout from '$components/layout/diligence/Layout.svelte';
</script>

<Layout>
	<main class="flex flex-1 flex-col items-center pb-40 overflow-scroll">
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
				従業員登録
			</h1>

			<label for="employee_name" class="pl-1 text-gray-500">従業員氏名</label>
			<input
				id="employee_name"
				type="text"
				name="EMPLOYEE_NAME"
				value=""
				class="input input-warning input-bordered w-full"
			/>

			<label for="employee_name_sub" class="pl-1 text-gray-500">従業員氏名（カナ）</label>
			<input
				id="employee_name_sub"
				type="text"
				name="EMPLOYEE_NAME_SUB"
				value=""
				class="input input-warning input-bordered w-full"
			/>

			<label for="birthday_year" class="pl-1 text-gray-500">生年月日</label>
			<div class="flex items-center">
				<input
					id="birthday_year"
					type="number"
					name="BIRTHDAY_YEAR"
					value=""
					class="input input-warning input-bordered w-full"
				/>
				<label for="birthday_year" class="px-2 text-gray-500">年</label>

				<input
					id="birthday_month"
					type="number"
					name="BIRTHDAY_MONTH"
					value=""
					class="input input-warning input-bordered w-full"
				/>
				<label for="birthday_month" class="px-2 text-gray-500">月</label>

				<input
					id="birthday_day"
					type="number"
					name="BIRTHDAY_DAY"
					value=""
					class="input input-warning input-bordered w-full"
				/>
				<label for="birthday_day" class="px-2 text-gray-500">日</label>
			</div>

			<label for="employee_gender" class="pl-1 text-gray-500">性別</label>
			<select
				id="employee_gender"
				name="EMPLOYEE_GENDER"
				class="select select-warning select-bordered w-full"
			>
				<option selected disabled>性別を選択してください</option>
				<option value="1">男</option>
				<option value="2">女</option>
				<option value="3">その他</option>
			</select>

			<label for="employee_zipcode" class="pl-1 text-gray-500">郵便番号</label>
			<input
				id="employee_zipcode"
				type="number"
				name="EMPLOYEE_ZIPCODE"
				value=""
				class="input input-warning input-bordered w-full"
			/>

			<label for="employee_address" class="pl-1 text-gray-500">住所</label>
			<input
				id="employee_address"
				type="text"
				name="EMPLOYEE_ADDRESS"
				value=""
				class="input input-warning input-bordered w-full"
			/>

			<label for="employee_phone" class="pl-1 text-gray-500">電話番号</label>
			<input
				id="employee_phone"
				type="text"
				name="EMPLOYEE_PHONE"
				value=""
				class="input input-warning input-bordered w-full"
			/>

			<label for="employee_email" class="pl-1 text-gray-500">メールアドレス</label>
			<input
				id="employee_email"
				type="email"
				name="EMPLOYEE_EMAIL"
				value=""
				class="input input-warning input-bordered w-full"
			/>

			<label for="employee_password" class="pl-1 text-gray-500">パスワード</label>
			<input
				id="employee_password"
				type="password"
				name="EMPLOYEE_PASSWORD"
				value=""
				class="input input-warning input-bordered w-full"
			/>

			<label for="employee_type" class="pl-1 text-gray-500">従業員タイプ</label>
			<select
				id="employee_type"
				name="EMPLOYEE_TYPE"
				class="select select-warning select-bordered w-full"
			>
				<option selected disabled>従業員タイプを選択してください</option>
				<option value="1">店長</option>
				<option value="2">正社員</option>
				<option value="3">アルバイト</option>
			</select>

			<label for="birthday_year" class="pl-1 text-gray-500">入社年月日</label>
			<div class="flex items-center">
				<input
					id="company_join_yaer"
					type="number"
					name="COMPANY_JOIN_YEAR"
					value=""
					class="input input-warning input-bordered w-full"
				/>
				<label for="company_join_yaer" class="px-2 text-gray-500">年</label>

				<input
					id="company_join_month"
					type="number"
					name="COMPANY_JOIN_MONTH"
					value=""
					class="input input-warning input-bordered w-full"
				/>
				<label for="company_join_month" class="px-2 text-gray-500">月</label>

				<input
					id="company_join_day"
					type="number"
					name="COMPANY_JOIN_DAY"
					value=""
					class="input input-warning input-bordered w-full"
				/>
				<label for="company_join_day" class="px-2 text-gray-500">日</label>
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
				登録
			</button>
		</div>
	</main>
</Layout>
