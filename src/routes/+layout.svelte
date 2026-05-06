<script lang="ts">
	import favicon from '$lib/assets/favicon.ico';
	import hackclub from '$lib/assets/hackclub.png';
	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>
<nav>
	<div class='bigboylogo'>
		<a href="https://hackclub.com/">
			<img src={hackclub} alt='hackclub.com'>
		</a>
	</div>
</nav>

{@render children()}
