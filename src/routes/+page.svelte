<script>
	import { Heading, P, Button, Card  } from 'flowbite-svelte';
	import { ArrowRightOutline } from 'flowbite-svelte-icons';
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcome_fallback from '$lib/images/svelte-welcome.png';
</script>

<svelte:head>
	<title>Pense</title>
	<meta name="description" content="Pense" />
</svelte:head>

<div class="flex justify-center text-center p-8 mt-16 md:width-2/3 min-h-screen">
	<Heading tag="h1" class="mb-4" customSize="text-4xl font-extrabold  md:text-5xl lg:text-6xl">Building the new Internet</Heading>
	<P class="mb-6 text-lg text-center lg:text-xl sm:px-16 xl:px-48 dark:text-gray-400">Pense builds digital products for well-known Web 3.0 brands <br>
	We team up with top developers and designers to make your ideas come to life</P>
	<Button href="/">
	  Learn more
	  <ArrowRightOutline class="w-3.5 h-3.5 ml-2" />
	</Button>
	<div class="mt-8 p-8">
		<Heading>Clients</Heading>
		<Card img="https://variety.com/wp-content/uploads/2023/01/Twitter-Third-Party-Apps.png" href="https://icx.one" horizontal class="mb-4" size="lg">
			<h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">ICX Social Network</h5>
			<p class="mb-3 font-normal text-gray-700 dark:text-gray-400 leading-tight text-left">We are working together with ICX One to develop a social network similar to Twitter with many extra cool features.</p>
		</Card>
	</div>
</div>