<script>
    import Link from "../lib/components/Link.svelte"
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>

<Link href="/" color="ghost">Ahoj <!-- Zde funguje ten @render children() --></Link>
<Link href="/" color="green">Ahoj</Link>