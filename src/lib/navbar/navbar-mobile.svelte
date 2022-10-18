<script>
	import NavbarMobileItem from './navbar-mobile-item.svelte';
</script>

<div
	class="d-none navbar-menu position-fixed top-0 start-0 bottom-0 w-75 mw-sm"
	style="z-index: 9999;"
>
	<div
		class="navbar-close position-fixed top-0 start-0 end-0 bottom-0 bg-dark"
		style="opacity: 75%;"
	/>
	<nav
		class="position-relative h-100 w-100 d-flex flex-column w-75 mw-sm py-10 px-6 bg-dark overflow-auto"
	>
		<div class="d-flex align-items-center mb-6">
			<a class="me-auto h4 mb-0 text-decoration-none" href="#">
				<span class="text-white">iForal</span>
			</a>
			<button class="btn navbar-close" type="button" aria-label="Close">
				<img src="pstls-assets/images/navigations/x.svg" alt="" />
			</button>
		</div>
		<div class="input-group" style="background-color: #2C2C2C;">
			<input
				class="form-control bg-transparent border-0"
				type="search"
				placeholder="Search"
				aria-label="Search"
				aria-describedby="search-addon"
			/>
			<button class="btn" type="button">
				<img src="pstls-assets/images/navigations/search-light.svg" alt="" />
			</button>
		</div>
		<div class="my-auto">
			<ul class="nav flex-column">
				<NavbarMobileItem href="/">Home</NavbarMobileItem>
				<NavbarMobileItem href="/team">Equipa</NavbarMobileItem>
				<NavbarMobileItem href="/news">Agenda</NavbarMobileItem>
				<NavbarMobileItem href="/posts">Publicações</NavbarMobileItem>
			</ul>
		</div>
	</nav>
</div>
