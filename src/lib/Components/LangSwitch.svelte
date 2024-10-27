<div id="loginContainer" class="relative">
	<div class="selected flex items-center cursor-pointer w-auto border rounded p-2 bg-gray-200">
		<i class="fas fa-language text-xl" aria-hidden="true"></i>
		<span>Svenska</span>
		<i class="fas fa-caret-down ml-2 text-xl" aria-hidden="true"></i>
	</div>
	<div class="options absolute z-10 bg-white border rounded shadow hidden">
		<div class="option flex items-center p-2 cursor-pointer hover:bg-gray-200">
			<i class="fas fa-language text-xl" aria-hidden="true"></i>
			<span class="ml-2">Svenska</span>
		</div>
		<div class="option flex items-center p-2 cursor-pointer hover:bg-gray-200">
			<i class="fas fa-language text-xl" aria-hidden="true"></i>
			<span class="ml-2">English</span>
		</div>
		<!-- Add more options as needed -->
	</div>
</div>

<style>
	#loginContainer {
		position: relative;
		width: 200px; /* Adjust as needed */
	}

	.options {
		display: none; /* Hide initially; show on click with JavaScript if needed */
		position: absolute;
		width: 100%;
		max-height: 200px;
		overflow-y: auto;
		border: 1px solid rgba(128, 128, 128, 0.7);
		background: white;
		z-index: 10;
	}

	.selected:hover + .options,
	.options:hover {
		display: block; /* Show options when hovering */
	}

	.option {
		display: flex;
		align-items: center;
		padding: 0.5rem;
		cursor: pointer;
	}

	.option:hover {
		background: rgba(128, 128, 128, 0.2);
	}
</style>
