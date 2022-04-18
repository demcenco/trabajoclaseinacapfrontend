<script>
	import GalItem from '$lib/GalItem.svelte';
</script>

<div class="flex flex-col items-center justify-center my-4">
	<div class="text-4xl font-bold text-yellow-500"> Galeria</div>
	<div class="max-w-5xl m-auto p-5">
		<div class="grid grid-cols-2 gap-4">
			<GalItem img="./fix.jpg" />
			<GalItem img="./tools.jpg" />
			<GalItem img="./diag.jpg" />
		</div>
	</div>
</div>
