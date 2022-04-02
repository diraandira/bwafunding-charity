<script>
	export let name;
</script>

<main>
	<h1>Hello {name}!</h1>
	<p>Visit the <a href= "https://svelte.dev/tetorial">Svelte tutorial </a>/>
</main>
<footer>&copy: 2020 All right reserved.</footer>
	
<style>
	main {
		text-align: center;
		padding: lem;
		max-width: 240px;
		margin: 0 auto;
	}
	
h1 {
	color: #ff3e00;
	text-transfrom: uppercase;
	font-size: 4em;
	font-weight: 100;
}
div{
	border: 0.5em solid #1a1a1a;
	padding: lem;
}
</style>

<svelte:head>
	<link
	href="https://cdn.rawgit.com/kimeiga/bahunya/css/bahunya-0.1.3.css"
	rel="stylesheet" />
</svelte:head>

<div>
	<h1>(title)</h1>
	<CharityList charities={charities}/>
</div>
