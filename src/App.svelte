<script>
	export let name;
	import Card from "./Card.svelte";
	import Nav from "./Nav.svelte";
</script>

<header>
	<Nav></Nav>
</header>


<main>
	<h1>Svelte First Exercise</h1>
	<!-- <h1>Hello {name}!</h1> -->
	<!-- <p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p> -->
	
	<Card></Card>


</main>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Cherry+Bomb+One&display=swap');
	@import url('https://fonts.googleapis.com/css2?family=Rubik+Puddles&display=swap');

	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		font-family:'Cherry Bomb One', georgia;
		color: pink;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	p{
		font-family: cursive;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>