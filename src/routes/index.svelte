<form action="./navigate">
	<div
		class="
					flex flex-col
					justify-center
					items-center
					w-full
					h-screen
					bg-gray-100
				"
	>
		<div class="flex flex-col w-96 mx-auto gap-2">
			<h1 class="text-center text-2xl md:text-3xl font-medium text-gray-800">サインイン</h1>

			<label for="email" class="pl-2 text-gray-500">メールアドレス</label>
			<input
				type="text"
				id="email"
				name="EMPLOYEE_EMAIL"
				class="input input-info input-bordered w-full"
			/>

			<label for="password" class="pl-2 text-gray-500">パスワード</label>
			<input
				type="password"
				id="password"
				name="EMPLOYEE_PASSWORD"
				class="input input-info input-bordered w-full"
			/>

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
				サインイン
			</button>
		</div>
	</div>
</form>
