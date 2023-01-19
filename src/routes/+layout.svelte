<script>
	import '../app.postcss';
	import './styles.css';
	import Navbar from '../components/Navbar.svelte';
	import Footer from '../components/Footer.svelte';
</script>

<div class="app bg-neutral-900 ">
	<Navbar />

	<main class="mx-20">
		<slot />
	</main>

	<Footer />
</div>

<style>
	.app {
		width: 100vh;
	}
</style>
