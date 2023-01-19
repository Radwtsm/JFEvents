<script>
	import { Navbar, NavBrand, NavLi, NavUl, NavHamburger } from 'flowbite-svelte';
</script>

<Navbar let:hidden let:toggle color="none">
	<NavBrand href="/">
		<span class="self-center whitespace-nowrap text-xl font-semibold text-white"> JF Events </span>
	</NavBrand>
	<NavHamburger on:click={toggle} />
	<NavUl {hidden}>
		<NavLi href="/televisione">Televisione</NavLi>
		<NavLi href="/cinema">Cinema</NavLi>
		<NavLi href="/grandieventi">Grandi Eventi</NavLi>
	</NavUl>
</Navbar>

<style>
</style>
