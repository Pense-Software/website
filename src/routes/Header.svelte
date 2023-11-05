<script>
	import { Navbar, NavBrand, NavLi, NavUl, NavHamburger, ImagePlaceholder, Skeleton, TextPlaceholder } from 'flowbite-svelte';
	import { page } from '$app/stores';
	import logo from '$lib/images/pense-logo-zoom.png';
	import github from '$lib/images/github.svg';
</script>

<Navbar class="px-2 sm:px-4 py-2.5 fixed w-full z-20 top-0 left-0 border-b mb-4">
	<NavBrand href="/">
	<img src={logo} class="mr-3 h-6 sm:h-9" alt="Pense Logo" />
	<span class="self-center whitespace-nowrap text-xl font-semibold dark:text-white">Pense</span>
	</NavBrand>
	<NavHamburger />
	<NavUl>
		<NavLi href="/" active={true}>Expertise</NavLi>
		<NavLi href="/">Work</NavLi>
		<NavLi href="/">About</NavLi>
		<NavLi href="/">Careers</NavLi>
		<NavLi href="/">Blog</NavLi>
		<NavLi href="/">Contact</NavLi>	
	</NavUl>
</Navbar>
