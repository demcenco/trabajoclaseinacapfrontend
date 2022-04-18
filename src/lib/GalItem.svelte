<script>
	export let img;
	let options = [1, 2, 3, 4];
	let rotate = Math.floor(Math.random() * options.length);
	let neg = Math.floor(Math.random() * 2);
	console.log(neg);
	console.log(rotate);
	$: option = neg < 1 ? `-rotate-${rotate}` : `rotate-${rotate}`;
</script>

<div
	class={`card card-compact  bg-base-100 shadow-xl  ${option} hover:scale-125 hover:z-10 duration-300`}
>
	<figure class="scale"><img alt="Gal" src={img} /></figure>
</div>
