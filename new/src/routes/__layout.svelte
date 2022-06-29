<script lang="ts">
	import Header from '$lib/header/Header.svelte';
	import '../app.scss';
</script>

<div class="app">
	<Header />

	<main class="container">
		<slot />
	</main>
	
	<footer>
		<p>visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to learn SvelteKit</p>
	</footer>
</div>

<style lang="scss">
	.app {
		background-color: purple;
	}
	main {
		background: grey;
	}
</style>
