<script>
	import NavbarItem from './navbar-item.svelte';
	import NavbarLanguage from './navbar-language.svelte';
</script>

<nav class="navbar py-10 navbar-expand-lg navbar-dark bg-dark">
	<div class="container">
		<a class="navbar-brand" href="/">
			<span class="text-white">iForal</span>
		</a>
		<button class="btn p-0 d-lg-none navbar-burger">
			<svg width="24" height="24" fill="none" xmlns="http://www.w3.org/2000/svg">
				<path
					fill-rule="evenodd"
					clip-rule="evenodd"
					d="M3.5 7C3.22386 7 3 6.77614 3 6.5C3 6.22386 3.22386 6 3.5 6H20.5C20.7761 6 21 6.22386 21 6.5C21 6.77614 20.7761 7 20.5 7H3.5ZM3.5 12C3.22386 12 3 11.7761 3 11.5C3 11.2239 3.22386 11 3.5 11H20.5C20.7761 11 21 11.2239 21 11.5C21 11.7761 20.7761 12 20.5 12H3.5ZM3 16.5C3 16.7761 3.22386 17 3.5 17H20.5C20.7761 17 21 16.7761 21 16.5C21 16.2239 20.7761 16 20.5 16H3.5C3.22386 16 3 16.2239 3 16.5Z"
					fill="#fff"
				/>
			</svg>
		</button>
		<div class="collapse navbar-collapse">
			<ul class="navbar-nav ms-1 mb-2 mb-lg-0">
				<li class="nav-item">
					<NavbarItem href="/">Home</NavbarItem>
				</li>
				<li class="nav-item">
					<NavbarItem href="/team">Team</NavbarItem>
				</li>
				<li class="nav-item">
					<NavbarItem href="/news">Notícias</NavbarItem>
				</li>
				<li class="nav-item">
					<NavbarItem href="/posts">Publicações</NavbarItem>
				</li>
			</ul>
			<div class="ms-auto">
				<div class="input-group" style="background-color: #2C2C2C; z-index: 10">
					<input
						style="z-index: 10;"
						class="form-control text-white bg-transparent border-0"
						placeholder="Pesquisar no site..."
					/>
					<button class="btn" type="button">
						<img src="pstls-assets/images/navigations/search-light.svg" alt="" />
					</button>
				</div>
			</div>
			<div>
				<NavbarLanguage />
			</div>
		</div>
	</div>
</nav>
