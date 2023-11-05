<script>
	import { page } from '$app/stores';
	import { onMount } from 'svelte';

	onMount(() => {
		console.log('mounted');
	});

	$: console.log($page);
</script>

<h1 class="text-3xl">Welcome to SvelteKit</h1>
<pre><code
		>{JSON.stringify($page, null, 2)}
    </code>
</pre>
