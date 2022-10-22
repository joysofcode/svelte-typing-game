<script lang="ts">
	import '../styles/app.scss'
</script>

<svelte:head>
	<title>Sveltype</title>
</svelte:head>

<div class="layout">
	<nav>
		<h1>🔥 sveltype</h1>
	</nav>

	<main>
		<slot />
	</main>
</div>

<style lang="scss">
	h1 {
		font-family: 'Lexend Deca', sans-serif;
		font-size: 1.8rem;
		color: var(--fg-200);
		letter-spacing: 2px;
	}

	.layout {
		height: 100%;
		display: grid;
		grid-template-rows: auto 1fr;
		align-items: center;
		padding: 2rem;
	}
</style>
