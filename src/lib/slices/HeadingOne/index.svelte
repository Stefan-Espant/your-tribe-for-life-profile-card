<script>
	/** @type {import("@prismicio/client").Content.HeadingOneSlice} */
	export let slice;

	// console.log(data)
</script>

<div data-slice-type={slice.slice_type} data-slice-variation={slice.variation}>
	<h1>{slice.primary.headingone[0].text}</h1>
</div>
<!-- 
<pre>
	{JSON.stringify(slice, null, 3)}
</pre> -->