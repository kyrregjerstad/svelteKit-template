<script lang="ts">
	import * as config from "$config";
	import MetaTags from "$lib/components/SEO/MetaTags.svelte";
	import "$styles/app.postcss";
</script>

<svelte:head>
	<title>{config.title}</title>
</svelte:head>
<MetaTags />

<main>
	<slot />
</main>

<style lang="postcss">
</style>
