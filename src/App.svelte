<script lang="ts">
	export let name: string;
</script>

<main>
	<div class="container mx-auto">
		<div class="text-lg font-bold">Hello {name}!</div>
	</div>
</main>

<style lang="postcss" global>
	@tailwind base;
	@tailwind components;
	@tailwind utilities;
</style>
