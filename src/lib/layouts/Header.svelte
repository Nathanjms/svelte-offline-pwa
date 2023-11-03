<script>
	import { page } from '$app/stores';
</script>

<header class="bg-slate-200">
	<nav class="container mx-auto">
		<ul class="flex gap-1 py-3">
			<li aria-current={$page.url.pathname === '/' ? 'page' : undefined}>
				<a href="/">Home</a>
			</li>
			<li aria-current={$page.url.pathname === '/test-page' ? 'page' : undefined}>
				<a href="/test-page">Test Page</a>
			</li>
		</ul>
	</nav>
</header>
