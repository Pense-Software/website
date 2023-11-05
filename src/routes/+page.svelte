<script>
	import { Skeleton, ImagePlaceholder, TextPlaceholder } from 'flowbite-svelte';
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcome_fallback from '$lib/images/svelte-welcome.png';
</script>

<svelte:head>
	<title>Pense</title>
	<meta name="description" content="Pense" />
</svelte:head>

<div style="height:300px;" class="overflow-scroll pb-16">
	<Skeleton class="mt-16 mb-8" />
	<ImagePlaceholder class="my-8" />
	<TextPlaceholder class="my-8" />
</div>
