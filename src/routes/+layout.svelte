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

