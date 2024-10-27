<script lang="ts">
</script>

<div id="container">
	<h1>Obegränsat med filmer, serier och annat</h1>
	<p>Obegränsat med filmer, serier och annat</p>
	<input type="text" id="email" />

	<button class=" bg-red-300">Register</button>
</div>

<style>
	h1 {
		margin-bottom: 0.5rem;
	}
	p {
		margin-bottom: 1rem;
	}
	#container {
		max-width: 31.75rem;
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

	div {
		color: white;
		min-height: 31rem;
		margin: -2rem auto 0 auto;
		display: -webkit-box;
		display: -webkit-flex;
		display: -ms-flexbox;
		display: flex;
		-webkit-flex-direction: column;
		-ms-flex-direction: column;
		flex-direction: column;
		min-height: 80vh;
		width: 100%;
		max-width: 120rem;
		-webkit-box-pack: center;
		-ms-flex-pack: center;
		-webkit-justify-content: center;
		justify-content: center;
		padding: 0 2rem 2rem 2rem;
	}
</style>
