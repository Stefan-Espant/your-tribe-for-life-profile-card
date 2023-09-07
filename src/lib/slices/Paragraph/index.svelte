<script>
	/** @type {import("@prismicio/client").Content.ParagraphSlice} */
	export let slice;
</script>

<div data-slice-type={slice.slice_type} data-slice-variation={slice.variation}>
	<p>{slice.primary.paragraph[0].text}</p>
</div>

<!-- <pre>
	{JSON.stringify(slice, null, 3)}
</pre> -->

<style>
	p {
		max-width: 30em;
		margin-bottom: 1em;
	}
</style>