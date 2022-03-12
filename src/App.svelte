<script>
	export let name;
</script>

<main>
	<h1>Hallo {name}!</h1>
	<p>Das ist ein nicht funktionaler Link <a href="https://führt.zu.nichts">Link</a></p>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>