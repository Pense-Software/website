<script>
	import Header from './Header.svelte';
	import './styles.css';
</script>

<div class="app">
	<!-- <Header /> -->
	<nav class="bg-white shadow-lg">
		<div class="container mx-auto px-6 py-3">
		  <div class="flex items-center justify-between">
			<div class="text-xl font-semibold text-gray-700">
			  <a href="#" class="text-gray-800 text-xl font-bold hover:text-gray-700">Pense</a>
			</div>
			<div class="flex items-center">
			  <div class="hidden md:flex space-x-1">
				<a href="#" class="py-2 px-3 text-gray-700 hover:bg-gray-200">Home</a>
				<a href="#" class="py-2 px-3 text-gray-700 hover:bg-gray-200">About Us</a>
				<a href="#" class="py-2 px-3 text-gray-700 hover:bg-gray-200">Our Services</a>
				<a href="#" class="py-2 px-3 text-gray-700 hover:bg-gray-200">Projects</a>
				<a href="#" class="py-2 px-3 text-gray-700 hover:bg-gray-200">Contact</a>
			  </div>
			</div>
		  </div>
		</div>
	  </nav>

	  <!-- Hero Section -->
  <header class="bg-gray-800 text-white">
    <div class="container mx-auto px-6 py-16 text-center">
      <h1 class="text-4xl font-bold mb-2">Innovative Web3 & Crypto Solutions</h1>
      <h2 class="text-2xl mb-8">Developing the digital future with blockchain technology</h2>
      <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
        Get Started
      </button>
    </div>
  </header>

  <!-- Services Section -->
  <section class="container mx-auto px-6 py-8">
    <h3 class="text-gray-700 text-3xl font-medium">Our Services</h3>
    <p class="text-gray-600 mt-4">We specialize in decentralized applications, smart contract development, and custom blockchain solutions.</p>
    <!-- Add more content here -->
  </section>

	<main>
		<slot />
	</main>

	<!-- Footer -->
	<footer class="bg-white">
		<div class="container mx-auto px-6 py-4">
		  <div class="flex justify-between items-center">
			<p class="text-gray-700 text-sm">© 2023 Pense. All Rights Reserved.</p>
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
