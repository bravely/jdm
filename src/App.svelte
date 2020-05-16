<script>
	import Header from './Header.svelte'
</script>

<svelte:head>
	<link href="https://fonts.googleapis.com/css2?family=Fira+Code&family=Jost:wght@500&family=Merriweather&display=swap" rel="stylesheet">
</svelte:head>

<div>
	<Header />
	<main>
		<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
		<code>Hello what => hi</code>
	</main>
</div>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>