<script>
	import Index from './routes/Index.svelte'
	import Nav from './routes/Nav.svelte'
	import Banner from './routes/Banner.svelte'

	let title = "AI FOR SOCIAL GOOD"
</script>

<Nav />

<Banner title = {title} />

<Index />

<style>

</style>