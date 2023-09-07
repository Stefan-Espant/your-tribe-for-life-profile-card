<script>
	/** @type {import("@prismicio/client").Content.GithubLinkSlice} */
	export let slice;
</script>

<div data-slice-type={slice.slice_type} data-slice-variation={slice.variation}>
	<a href={slice.primary.githublink.url}>Bezoek mijn Github</a>
</div>

<!-- <pre>
	{JSON.stringify(slice, null, 3)}
</pre> -->
