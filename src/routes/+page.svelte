<script>
    import ComponentCard from "$lib/site/ComponentCard.svelte";

    import Navbar from '$lib/site/Navbar.svelte';
    import Footer from '$lib/site/Footer.svelte';

</script>

<svelte:head>
    <title>UI Components - Sam Liu</title>
</svelte:head>

<Navbar />

<!-- Title -->
<div class="py-32 text-center bg-gradient-to-br from-indigo-100 to-blue-300 dark:from-cyan-700 dark:to-blue-900">
    <h1 class="text-7xl font-medium dark:text-white">UI Components</h1>
    <p class="mt-6 text-lg text-slate-600 dark:text-slate-300">A collection of my experimentation with building UI components.</p>
</div>

<!-- Cards -->
<div class="py-16 px-64 grid grid-cols-3 gap-12 xl:-2xl:px-32 xs:-xl:px-16 md:-lg:grid-cols-2 -md:grid-cols-1 2xs:-xs:px-8 -2xs:px-0 -2xs:gap-6 -2xs:divide-y-2 dark:divide-slate-700">
    <!-- CC0 placeholder image by Ryan Klaus -->
    <ComponentCard title="Button" description="A button component with a variety of styles and sizes." thumbnail="https://images.pexels.com/photos/13235188/pexels-photo-13235188.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" href="/button" />
    <ComponentCard title="Button" description="A button component with a variety of styles and sizes." thumbnail="https://images.pexels.com/photos/13235188/pexels-photo-13235188.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" href="/" />
    <ComponentCard title="Button" description="A button component with a variety of styles and sizes." thumbnail="https://images.pexels.com/photos/13235188/pexels-photo-13235188.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" href="/" />
    <ComponentCard title="Button" description="A button component with a variety of styles and sizes." thumbnail="https://images.pexels.com/photos/13235188/pexels-photo-13235188.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" href="/" />
    <ComponentCard title="Button" description="A button component with a variety of styles and sizes." thumbnail="https://images.pexels.com/photos/13235188/pexels-photo-13235188.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" href="/" />
    <ComponentCard title="Button" description="A button component with a variety of styles and sizes." thumbnail="https://images.pexels.com/photos/13235188/pexels-photo-13235188.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" href="/" />
</div>

<footer class="bg-white dark:bg-slate-900">
    <Footer />
</footer>