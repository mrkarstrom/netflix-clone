<script lang="ts">
	import LangSwitch from './LangSwitch.svelte';
	import Logo from './Logo.svelte';
</script>

<div class="w-full h-auto flex justify-between items-center absolute top-0 container">
	<Logo />
	<div class="max-w-7xl flex w-auto items-center h-[80px]">
		<div class="item">
			<LangSwitch />
		</div>
		<div class="item">User</div>
	</div>
</div>

<style>
</style>
