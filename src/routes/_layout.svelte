<script>
	import Nav from './_components/Nav.svelte'

	import Footer from './_components/Footer.svelte'

	export let segment
</script>

<style>
</style>

<Nav {segment}/>

<main class="section">
	<slot></slot>
</main>

<Footer />