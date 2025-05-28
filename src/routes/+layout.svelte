<script lang="ts">
	import '../app.css';
	import Pagina from '../components/templates/Pagina.svelte';

	let { children } = $props();
</script>

<div class="fonte-principal">
	<Pagina>
		{@render children()}
	</Pagina>
</div>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Red+Hat+Text:ital,wght@0,300..700;1,300..700&display=swap');

	.fonte-principal {
		font-family: "Red Hat Text", sans-serif;
	}
</style>