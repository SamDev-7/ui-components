<script>
	import '../app.css';

    import Navbar from '$lib/site/Navbar.svelte';
    import Footer from '$lib/site/Footer.svelte';

    import { scroll } from '$lib/site/utils/scroll';

	function scrollHandler() {
		scroll.set(window.scrollY);
	}

</script>

<svelte:window on:scroll={scrollHandler} />

<Navbar />

<main class="bg-white dark:bg-slate-900">
	<slot />
</main>

<footer class="bg-white dark:bg-slate-900">
    <Footer />
</footer>