<script>
	import '../app.css';
	import Header from '$lib/layouts/Header.svelte';
</script>

<div class="app min-h-screen flex flex-col justify-between">
	<div>
		<Header />

		<main class="container mx-auto">
			<slot />
		</main>
	</div>
	<div>
		<footer class="container mx-auto">Footer!</footer>
	</div>
</div>
