<script lang="ts">
	import { language } from '$lib/language';

	export let name: string;
	export let description: string;
	export let image: string;
	export let link: string;
	export let topics: string | undefined = undefined;
	export let topicsEn: string | undefined = undefined;

	let showAbout = false;
</script>

{#if showAbout}
	<div
		style="width: 100%; height:100vh; position:fixed; z-index: 10; right:0; top:0; background: rgba(0,0,0,0.5); display:flex; justify-items: center; align-items: center;"
	>
		<div
			class="bg-white p-8"
			style="width: 100%; height:100%; max-width: 720px; max-height: 600px; margin:auto; overflow-y: auto; border-radius: 5px;"
		>
			<div style="display: flex; justify-content: space-between;" class="mb-4">
				<h3 class="lh-sm font-heading">
					{#if $language === 'pt'}
						Sobre
					{:else}
						About
					{/if}
				</h3>
				<button class="btn" on:click={() => (showAbout = false)}>X</button>
			</div>
			<p style="text-align: justify; margin-top:14px;">
				{#if $language === 'pt'}
					<slot name="pt" />
				{:else}
					<slot name="en" />
				{/if}
			</p>
			{#if $language === 'pt'}
				<span class="text-muted">{topics}</span>
			{:else}
				<span class="text-muted">{topicsEn}</span>
			{/if}
		</div>
	</div>
{/if}

<div class="mx-auto mw-xs px-7">
	<div class="position-relative mb-12">
		<img
			class="img-fluid position-relative"
			src={image}
			style="z-index: 1; object-fit: cover; width: 300px; height:300px"
			alt={description}
		/>
		<div class="bg-primary-light position-absolute start-0 top-0 w-100 h-100 mt-6 ms-n6" />
	</div>
	<h5 class="mb-0 fw-bold lh-lg font-heading">
		{name}
	</h5>
	<span class="text-muted small">{description}</span>
	<div class="mt-2">
		<span
			style="color:black; margin-right:10px; cursor:pointer; text-decoration: underline;"
			on:click={() => (showAbout = true)}
		>
			{#if $language === 'pt'}
				Sobre
			{:else}
				About
			{/if}
		</span>
		<a style="color:black;" href={link} target="_blank">CV</a>
	</div>
</div>
