<script lang="ts">
	import { language } from '$lib/language';
</script>

<span class="nav-link">
	<img
		src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5c/Flag_of_Portugal.svg/600px-Flag_of_Portugal.svg.png?20210806190400"
		alt="português"
		class="mx-3"
		style={$language === 'pt'
			? 'width: 25px; cursor: pointer;'
			: 'width: 25px; cursor: pointer; filter: grayscale();'}
		on:click={() => language.set('pt')}
	/>
	<img
		src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f2/Flag_of_Great_Britain_%281707–1800%29.svg/2560px-Flag_of_Great_Britain_%281707–1800%29.svg.png"
		alt="english"
		style={$language === 'en'
			? 'width: 25px; cursor: pointer;'
			: 'width: 25px; cursor: pointer; filter: grayscale();'}
		on:click={() => language.set('en')}
	/>
</span>
