<script>
    // import '$lib/styles/style.scss';
    import logo from '$lib/assets/shared/logo.svg'
</script>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Barlow+Condensed:wght@400;700&family=Bellefair&family=Barlow:wght@400;700&display=swap"
    rel="stylesheet">


<header class="primary-header">
    <div>
        <img src="{logo}" alt="space tourism logo" class="logo">
    </div>
    <nav>
        <ul class="primary-navigation underline-indicators flex">
            <li class="active">
                <a class="ff-sans-cond text-white uppercase letter-spacing-2" href="/"
                    ><span>00</span>Home</a
                >
            </li>
            <li>
                <a class="ff-sans-cond text-white uppercase letter-spacing-2" href="destination.html"
                    ><span>01</span>Destination</a
                >
            </li>
            <li>
                <a class="ff-sans-cond text-white uppercase letter-spacing-2" href="crew.html"
                    ><span>02</span>Crew</a
                >
            </li>
            <li>
                <a class="ff-sans-cond text-white uppercase letter-spacing-2" href="technology.html"
                    ><span>03</span>Technology</a
                >
            </li>
        </ul>
    </nav>
</header>
<slot />


<style lang="scss">

</style>