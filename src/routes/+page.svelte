<script>
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcome_fallback from '$lib/images/svelte-welcome.png';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Pense" />
</svelte:head>

<section>
	<h1>
		<span class="welcome">
			<!-- <picture>
				<source srcset={welcome} type="image/webp" />
				<img src={welcome_fallback} alt="Welcome" />
			</picture> -->
		</span>

		Pense
	</h1>

	<h2>
		Software Development Company
	</h2>

	<h2>
		Developing the digital future with blockchain technology. We specialize in decentralized applications, smart contract development, and custom blockchain solutions.
	</h2>


	<!-- <Counter /> -->
</section>
