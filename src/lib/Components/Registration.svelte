<script lang="ts">
</script>

<div
	class="text-white min-h-[31rem] md:min-h-[80vh] mx-auto mt-[-2rem] flex flex-col justify-center items-center w-full max-w-[120rem] px-8 pb-8"
>
	<div class="max-w-[31.75rem] text-center" id="container">
		<h1 class="mb-0.5">Obegränsat med filmer, serier och annat</h1>
		<p class="mb-1">Från 109 kr. Avsluta när du vill.</p>
		<h3>Redo att börja titta? Ange din e-postadress för att skapa eller återaktivera ett konto.</h3>
		<div class="flex items-start w-full" id="inputContainer">
			<input type="text" id="email" />
			<button class=" bg-red-300">Register</button>
		</div>
	</div>
</div>

<style>
	input {
		width: auto;
		-webkit-flex: 1 1 auto;
		-ms-flex: 1 1 auto;
		flex: 1 1 auto;
		flex-grow: 1;
		flex-shrink: 1;
		flex-basis: auto;
		font-size: 1rem;
		line-height: 1.5;
		width: 100%;
		padding: 1.5rem 1rem 0.5rem;
		background: rgba(22, 22, 22, 0.7);
		border-radius: 0.25rem;
		border-width: 0.0625rem;
		border-color: rgba(128, 128, 128, 0.7);
	}
	button {
		width: auto;
		font-size: 1.5rem;
		font-weight: 500;
		min-height: 3.5rem;
		padding: 0.75rem 1.5rem;
		border-radius: 0.25rem;
		background: rgb(229, 9, 20);
	}

	#inputContainer {
		text-align: center;
		box-sizing: border-box;
		max-width: 61.5rem;
		margin: 0 auto;
		padding: 0 1.5rem;
		content: '1';
		gap: 10px;
	}

	@media (min-width: 600px) {
		#container {
			max-width: 27rem;
		}
		p {
			font-size: 1rem;
			font-weight: 400;
		}
		h1 {
			font-size: 2rem;
			font-weight: 700;
		}
	}

	@media (min-width: 960px) {
		#container {
			max-width: 37rem;
		}
		h1 {
			font-size: 2.5rem;
			font-weight: 700;
		}
		p {
			margin: 0 0 24px;
		}

		h3 {
			color: rgb(255, 255, 255);
			font-size: 1rem;
			font-weight: 400;
			line-height: 1.5;
		}
	}
</style>
