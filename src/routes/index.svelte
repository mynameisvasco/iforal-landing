<script>
	import AboutEn from '$lib/home/about-en.svelte';
	import About from '$lib/home/about.svelte';
	import ContactEn from '$lib/home/contact-en.svelte';
	import Contact from '$lib/home/contact.svelte';
	import HomeHeader from '$lib/home/home-header.svelte';
	import ObjectivesEn from '$lib/home/objectives-en.svelte';
	import Objectives from '$lib/home/objectives.svelte';
	import Partners from '$lib/home/partners.svelte';
	import { language } from '$lib/language';
</script>

<div class="">
	<HomeHeader />
	<Partners />
	{#if $language === 'pt'}
		<About />
	{:else}
		<AboutEn />
	{/if}
	{#if $language === 'pt'}
		<Objectives />
	{:else}
		<ObjectivesEn />
	{/if}
	{#if $language === 'pt'}
		<Contact />
	{:else}
		<ContactEn />
	{/if}
</div>
