<!-- <h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p> -->

<script>
    import Navbar from '../components/Navbar.svelte';
    import Content from '../components/Content.svelte';
    import Footer from '../components/Footer.svelte';
</script>
<!-- height: 55.11%; -->
<!-- height: 44.89%; -->
<div class="h-screen flex flex-col relative" style="background: #24FFBC;">
    <div class="w-screen absolute" style="z-index: 0; height: 55.11%; background: linear-gradient(132deg, #0B0B0F, #1A1A22e5);"></div>
    <div class="w-screen absolute" style="z-index: 0; height: 44.89%; top: 55.11%; background: linear-gradient(126deg, #211A1A, #212127);"></div>
    <Navbar />
    <!-- <main class="flex-grow"> -->
    <Content />
    <!-- </main> -->
    <!-- <Footer /> -->
</div>
