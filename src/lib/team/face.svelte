<script lang="ts">
	export let description: string;
	export let image: string;
</script>

<div class="mx-auto mw-xs px-7">
	<div class="position-relative mb-12">
		<img class="img-fluid position-relative" src={image} style="z-index: 1" alt={description} />
		<div class="bg-primary-light position-absolute start-0 top-0 w-100 h-100 mt-6 ms-n6" />
	</div>
	<h5 class="mb-0 fw-bold lh-lg font-heading">
		<slot />
	</h5>
	<span class="text-muted small">{description}</span>
</div>
