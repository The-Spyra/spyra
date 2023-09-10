<script>
    import "../app.css";
</script>

<svelte:head>
    <title>Spyra</title>
    <link
        rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css"
        integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA=="
        crossorigin="anonymous"
        referrerpolicy="no-referrer"
    />
</svelte:head>

<header
    class="flex fixed h-12 top-0 left-0 w-screen text-white justify-between items-center px-10 py-10"
>
    <a href="/" class="font-bold text-4xl -tracking-[1.5px]">SPYRA</a>
    <nav>
        <ul class="flex gap-6 text-lg">
            <li><a class="transition-colors duration-500 bg-clip-text hover:text-transparent ease-in-out font-bold text-white bg-gradient-to-br from-yellow-500 to-red-500" href="/">Home</a></li>
            <li><a class="transition-colors duration-500 bg-clip-text hover:text-transparent ease-in-out font-bold text-white bg-gradient-to-br from-yellow-500 to-red-500" href="/about">About</a></li>
            <li><a class="transition-colors duration-500 bg-clip-text hover:text-transparent ease-in-out font-bold text-white bg-gradient-to-br from-yellow-500 to-red-500" href="/contact">Contact</a></li>
        </ul>
    </nav>
</header>

<div class="font-sans text-white">
    <slot />
</div>
