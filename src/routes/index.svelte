<script>
	import { pokemon } from '../stores/pokestore';
</script>

<h1>SvelteKit Pokedex</h1>

{#each $pokemon as pokeman}
	<p>{pokeman.name}</p>
{/each}
