<script>
	/** @type {import("@prismicio/client").Content.MainImageSlice} */
	export let slice;
	
</script>

<div data-slice-type={slice.slice_type} data-slice-variation={slice.variation}>
	<img src={slice.primary.mainimage.url} alt={slice.primary.mainimage.alt} width={slice.primary.mainimage.dimensions.width} height={slice.primary.mainimage.dimensions.height} />
</div>

<!-- <pre>
	{JSON.stringify(slice, null, 3)}
</pre> -->

<style>
	img {
		width: 12em;
		height: auto;
		aspect-ratio: 1/1;
		border-radius: 0.5em;
	}
</style>