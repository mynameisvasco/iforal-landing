<script lang="ts">
	export let title: string;
	export let image: string;
</script>

<div class="row align-items-md-center border-bottom pb-12 mt-12">
	<div class="col-12">
		<h2 class="mb-0 lh-sm font-heading">{title}</h2>
		<p class="mb-0 lh-lg">
			<slot />
		</p>
	</div>
</div>
