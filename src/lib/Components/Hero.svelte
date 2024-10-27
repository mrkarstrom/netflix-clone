<script lang="ts">
	import Registration from './Registration.svelte';
</script>

<div id="hero" class="w-full min-h-screen flex flex-col items-center justify-center">
	<div id="overlay" class="w-full min-h-screen flex flex-col items-center justify-center">
		<Registration />
	</div>
</div>

<style>
	#hero {
		background-image: url('/img/background_large.jpg');
	}

	#overlay {
		background-image: linear-gradient(
			360deg,
			rgba(0, 0, 0, 0.85) 3%,
			rgba(0, 0, 0, 0.8465) 11.08%,
			rgba(0, 0, 0, 0.8361) 19.17%,
			rgba(0, 0, 0, 0.8187) 27.25%,
			rgba(0, 0, 0, 0.7944) 35.33%,
			rgba(0, 0, 0, 0.7632) 43.42%,
			rgba(0, 0, 0, 0.725) 51.5%,
			rgba(0, 0, 0, 0.6868) 59.58%,
			rgba(0, 0, 0, 0.6556) 67.67%,
			rgba(0, 0, 0, 0.6313) 75.75%,
			rgba(0, 0, 0, 0.6139) 83.83%,
			rgba(0, 0, 0, 0.6035) 91.92%,
			rgba(0, 0, 0, 0.6) 100%
		);

		z-index: 1;
	}
</style>
