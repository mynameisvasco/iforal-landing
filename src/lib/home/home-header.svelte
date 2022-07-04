<script>
	import NavbarMobile from '$lib/navbar/navbar-mobile.svelte';
	import Navbar from '$lib/navbar/navbar.svelte';
	import Hero from './hero.svelte';
</script>

<section class="position-relative pb-24 position-relative overflow-hidden bg-dark">
	<img
		class="position-absolute top-0 end-0 h-100"
		src="pstls-assets/images/headers/shadow-right.png"
		alt=""
	/>
	<Navbar />
	<div class="container mt-12 pb-24">
		<div class="row">
			<Hero />
		</div>
	</div>
	<NavbarMobile />
</section>
