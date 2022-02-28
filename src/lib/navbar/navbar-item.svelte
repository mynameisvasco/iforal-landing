<script lang="ts">
	import { page } from '$app/stores';

	export let href: string;
</script>

<a
	class="nav-link"
	class:text-danger={$page.url.pathname === href}
	class:text-white={$page.url.pathname !== href}
	{href}
>
	<slot />
</a>
