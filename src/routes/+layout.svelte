<script>
	import favicon from '$lib/assets/favicon.png';

	let { children } = $props();

	export const prerender = true;
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

{@render children()}
