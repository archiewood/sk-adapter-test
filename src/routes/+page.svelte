<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<!-- Category Href links -->

{#each Array.from({ length: 1000000 }, (_, i) => i + 1) as i}
  <a href="/page{i}">{i}</a>
  <br/>
{/each}
