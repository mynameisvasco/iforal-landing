<script>
	import { page } from '$app/stores';
	import Footer from '$lib/footer/footer.svelte';
	import Navbar from '$lib/navbar/navbar.svelte';
	import '../scss/bootstrap-theme.scss';
</script>

<header>
	{#if $page.url.pathname !== '/'}
		<Navbar />
	{/if}
</header>
<main>
	<slot />
</main>
<footer>
	<Footer />
</footer>
