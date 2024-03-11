<script lang="ts">
	import Footer from '$lib/components/Footer.svelte';
	import Header from '$lib/components/Header.svelte';
	import Hero from '$lib/components/Hero.svelte';
	import Testimonials from '$lib/components/Testimonials.svelte';
</script>

<div class="container">
	<Header />
	<Hero />
	<Testimonials />
	<Footer />
</div>

<style>
	.container {
		width: 23.4375rem;
		display: block;
		margin-left: auto;
		margin-right: auto;
		height: 538px;
	}
</style>
