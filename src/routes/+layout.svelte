<script>
	import { onMount } from 'svelte';
	import { themeChange } from 'theme-change';
	import '../app.css';

	onMount(() => {
		themeChange(false);
	});
</script>

<main>
	<slot />
</main>
