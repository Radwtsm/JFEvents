<script>
	import '../app.postcss';
	import './styles.css';
	import Navbar from '../components/Navbar.svelte';
	import Footer from '../components/Footer.svelte';
</script>

<div class="app ">
	<Navbar />

	<main>
		<slot />
	</main>

	<Footer />
</div>

<style>
	.app {
		width: 100vh;
	}

	main {
		margin-right: 1rem;
		margin-left: 1rem;
	}
</style>
