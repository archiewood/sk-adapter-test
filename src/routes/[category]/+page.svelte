<script>
    import { page } from '$app/stores';
    // random number
</script>

{$page.params.category}

{#each Array.from({ length: 100 }, (_, i) => i + 1) as i}
    
    
    <br/>
    {Math.floor(Math.random() * 1000000)}
    
{/each}

