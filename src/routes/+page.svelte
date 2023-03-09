<Container>
    <h1>Welcome to SvelteKit</h1>
    <p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
    <span>{lang}</span>
</Container>

<script lang="ts">
    import Container from '../components/Container/container.svelte'
    const lang:string = 'OK' 
</script>