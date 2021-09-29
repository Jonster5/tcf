<script lang="ts">
	import Home from './home.svelte';

	type Tab = 'Home';

	let tab: Tab = 'Home';
</script>

<svelte:head>
	<title>tcf - {tab}</title>
</svelte:head>

{#if tab === 'Home'}
	<Home />
{/if}

<style>
</style>
