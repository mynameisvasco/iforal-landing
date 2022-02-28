<script lang="ts">
	export let href: string;
</script>

<li class="nav-item py-3">
	<a class="nav-link text-danger" {href}> <slot /></a>
</li>
