<script lang="ts">
	export let title: string;
	export let image: string;
</script>

<div class="row align-items-md-center border-bottom pb-12 mt-12">
	<div class="col-12 col-md-5 mb-6 mb-md-0">
		<img
			src={image}
			alt={title}
			style="width: 350px; height:200px; max-width: 100%; object-fit: cover; "
		/>
	</div>
	<div class="col-12 col-md-7">
		<h2 class="mb-0 lh-sm font-heading">{title}</h2>
		<p class="mb-0 lh-lg">
			If you have ever wondered how to develop your brand, this is the place for you. Take a big
			step forward in growing your business with this great tool.
		</p>
		<button class="btn btn-sm btn-dark mt-4"> Ler mais </button>
	</div>
</div>
