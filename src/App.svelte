<script lang="ts">
	import Router from 'svelte-spa-router';
	import Home from './routes/Home.svelte';
	import Navigation from "./components/Navigation.svelte";

	const routes = {
		'/' : Home,
	}
</script>

<main>
	<Navigation />
	<Router {routes} />
</main>

<style>
	main {
		text-align: center;
		width: 390px;
		height: 844px;
		margin: 0 auto;
		background-color: bisque;
	}
</style>