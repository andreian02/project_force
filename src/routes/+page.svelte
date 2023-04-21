<script>

	//import NetworkGraphCanvas from './NetworkGraphCanvas.svelte';
	//import GraphSvelteSVG from './NetworkGraphSvelteSVG.svelte';
	import NetworkGraphD3SVG from './force/NetworkGraphD3SVG.svelte';
	import data from './force/data2.js';
	
</script>


<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<p><a href="/force">Force</a></p>


<div class="chart">
	<NetworkGraphD3SVG graph={data} />
</div>




<style>
	.chart {
		width: max-content;
		height: max-content;
		margin: 0 auto;
	}
</style>