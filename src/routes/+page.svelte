<script>
	import { SliceZone } from '@prismicio/svelte';
	import { components } from '$lib/slices';

	export let data;
</script>

<main>
	<section>
		<SliceZone slices={data.slices} {components} />
	</section>

</main>

<style>
	main {
		width: 100%;
		height: 100vh;
		display: flex;
        background-image: linear-gradient(135deg, #b51616 0% , #e55959 10% , #e55959 20%, #512b9e 20%, #512b9e 20%, #b18aff 60%, #203ea8 60%, #203ea8 60%, #5178ff 100%);
        position: relative;
	}

	section {
		width: 20em;
		margin: auto;
		padding: 1em;
		background-color: #f4f4f44a;
        border-radius: 1em;
		z-index: 1;
	}
</style>
