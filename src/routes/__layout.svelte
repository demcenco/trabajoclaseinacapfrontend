<script>
	import Footer from '$lib/Footer.svelte';
	import Nav from '$lib/Nav.svelte';

	import '../app.css';
</script>

<div class="flex flex-col h-screen">
	<Nav />
	<div class="flex-grow   ">
		<slot />
	</div>
	<Footer />
</div>

<style>
	:global(.h-200) {
		height: 32em;
	}
</style>
