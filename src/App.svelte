<script>
	export let name;
	import Card from "./Card.svelte";
</script>

<main>
	<h1>Hello {name}!</h1>
	<!-- <p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p> -->
<Card>
<div>
	<img src="https://images.unsplash.com/photo-1596815064285-45ed8a9c0463?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=732&q=80" alt="profile picture" />
	<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium itaque neque assumenda!</p>
</div>
</Card>
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