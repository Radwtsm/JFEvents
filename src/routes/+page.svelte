<script>
	import Saos from 'saos';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<Saos animation={'fade-in 1s cubic-bezier(0.35, 0.5, 0.65, 0.95) both'}>
	<div class="flex flex-col justify-around h-screen">
		<h1 class="text-8xl ">Rendiamo speciali i tuoi momenti importanti.</h1>
		<button class="bg-white w-52 p-5 rounded-lg  ">scopri di più</button>
	</div>
</Saos>

<Saos animation={'fade-in 1s cubic-bezier(0.35, 0.5, 0.65, 0.95) both'}>
	<div class="text-white text-center mt-5 mb-5">
		<h2 class=" text-7xl mb-3 font-bold ">TEAM</h2>
		<img
			class="rounded-lg"
			src="https://www.solidbackgrounds.com/images/800x600/800x600-white-solid-color-background.jpg"
			alt=""
		/>
		<p class="mt-1 text-2xl">
			Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sapiente nisi esse maxime ipsa
			perspiciatis error cumque quod illum, consectetur veritatis.
		</p>
	</div>
</Saos>

<style>
	@keyframes -global-fade-in {
		0% {
			opacity: 0;
		}
		100% {
			opacity: 1;
		}
	}

	h1 {
		color: white;
	}
</style>
