<script>
	import { addTodo } from '../../store/TodoStore';
</script>

<section class="flex justify-between">
	<h3 class="text-xl font-bold text-olive-four">Checklist Section</h3>
	<button
		class="text-gray-five group flex items-center rounded-md border-cream-four bg-green-one px-6 py-3 text-lg font-semibold outline outline-2 outline-offset-2 outline-green-one hover:text-green-five focus-visible:text-green-five focus-visible:outline-green-five"
		type="button"
		on:click={addTodo}
		>Add Task
		<svg
			class="text-gray-five ml-3 h-4 w-4 focus-visible:text-green-four group-hover:text-green-four"
			width="42"
			height="42"
			viewBox="0 0 42 42"
			fill="currentColor"
			xmlns="http://www.w3.org/2000/svg"
		>
			<path
				d="M20.7168 5V37M36.7168 21H4.7168"
				stroke="black"
				stroke-width="9.42474"
				stroke-linecap="round"
				stroke-linejoin="round"
			/>
		</svg>
	</button>
</section>
