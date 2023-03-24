<script>
	import '../app.postcss';
	import SiteHeader from '$lib/components/SiteHeader.svelte';
	import SiteFooter from '$lib/components/SiteFooter.svelte';

</script>

<div class="app">
	<SiteHeader />

	<main>
		<slot />
	</main>

	<SiteFooter />
</div>


