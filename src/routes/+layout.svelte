<script lang="ts">
	import favicon from '$lib/assets/favicon.ico';
	import hackclub from '$lib/assets/hackclub.png';
	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>
<nav>
	<img src={hackclub} alt='hackclub.com'>
</nav>

{@render children()}
