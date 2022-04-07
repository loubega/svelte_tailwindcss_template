<script>
	export let name;
</script>

<div>
	<div class="w-52 bg-red-500 rounded-xl shadow-xl text-center">Hello {name}!</div>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</div>

<style global lang="postcss">
	@tailwind base;
	@tailwind components;
	@tailwind utilities;
</style>
