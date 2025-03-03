<script>
	import ThemeChange from '$lib/components/theme-change.svelte';
</script>

<div class="flex h-screen flex-col items-center justify-center">
	<ThemeChange />

	<h1
		class="from-primary to-secondary via-accent animate-gradient-xy bg-linear-to-tr bg-clip-text py-8 text-6xl font-extrabold text-transparent md:text-9xl"
	>
		Tailwind Gradient Text
	</h1>
	<p
		class="from-primary to-secondary via-accent animate-gradient-y bg-linear-to-br bg-clip-text py-8 text-3xl font-extrabold text-transparent md:text-6xl"
	>
		This animation is on the vertical axis
	</p>
	<p
		class="from-primary to-secondary via-accent animate-gradient-x bg-linear-to-tl bg-clip-text py-8 text-3xl font-extrabold text-transparent md:text-6xl"
	>
		This animation is on the horizontal axis
	</p>
</div>
