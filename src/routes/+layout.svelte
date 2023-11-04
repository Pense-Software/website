<script>
	import Header from './Header.svelte';
	import './styles.css';
</script>

<div class="app">
	<Header/>
	<!-- <main> -->
	<slot />
	<!-- </main> -->

	<!-- Footer -->
	<footer class="bg-white">
		<div class="container mx-auto px-6 py-4">
		  <div class="flex justify-between items-center">
			<p class="text-gray-700 text-sm">© 2023 Pense Lda.</p>
			<div class="flex">
			  <!-- Social Icons -->
			  <!-- Add social media links here -->
			</div>
		  </div>
		</div>
	  </footer>
</div>

<style>
	.app {
		display: flex;
		flex-direction: column;
		min-height: 100vh;
	}

	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		justify-content: start;
		align-items: start;
		padding: 1rem;
		width: 100%;
		max-width: 64rem;
		margin: 0 auto;
		box-sizing: border-box;
	}

	footer {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		padding: 12px;
	}

	footer a {
		font-weight: bold;
	}

	@media (min-width: 480px) {
		footer {
			padding: 12px 0;
		}
	}
</style>
