<script>
	import { Navbar, NavBrand, NavLi, NavUl, NavHamburger } from 'flowbite-svelte';
</script>

<Navbar let:hidden let:toggle color="none">
	<NavBrand on:click={toggle} href="/">
		<span class="self-center whitespace-nowrap text-xl font-semibold text-white"> JF Events </span>
	</NavBrand>
	<NavHamburger on:click={toggle} />
	<NavUl {hidden}>
		<NavLi on:click={toggle} href="/televisione">Televisione</NavLi>
		<NavLi on:click={toggle} href="/cinema">Cinema</NavLi>
		<NavLi on:click={toggle} href="/grandieventi">Grandi Eventi</NavLi>
	</NavUl>
</Navbar>

<style>
</style>
