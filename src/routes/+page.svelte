<script>
    let date = new Date();
    let year = date.getFullYear();
</script>

<main class="min-h-screen w-full">
    <div class="prose xl:prose-lg p-10 m-auto">
        <img src="/favicon.png" alt="Bild Atrium" class="m-auto w-52 h-auto" />

        <h1 class="m-auto text-center p-5">The HEGame (comming soon!)</h1>
        <p>Wilkommen beim HEGame!</p>
        <p>
            In diesem Spiel müssen Sie sich anhand von Hinweisen durch die
            Schule bewegen, um das Spiel zu gewinnen
        </p>
        <h2>Wie kann man mitspielen?</h2>
        <p>Downloaden Sie die App im App- oder Playstore, um mitzuspielen!</p>
    </div>

    <div class="w-full flex justify-center gap-4 items-center m-auto">
        <a href="/"
            ><img
                class="w-48 h-auto"
                src="/badges/google-play-badge.png"
                alt="PlayStore Badge"
            /></a
        >
        <a href="/"
            ><img
                class="w-48 h-auto"
                src="/badges/Download_on_the_App_Store_Badge_DE_RGB_blk_092917.svg"
                alt="AppStore Badge"
            /></a
        >
    </div>
</main>

<footer
    class="w-full p-4 grid place-items-center border-t-2 border-t-emerald-500 border-dotted"
>
    <section class="prose text-center">
        <p class="text-slate-500">
            Google Play und das Google Play-Logo sind Marken von Google LLC.
            <br />
            AppStore and iOS are trademarks of Apple Inc.
        </p>
        <p>
            &copy; {year}
            <a
                href="https://www.heg-uelzen.de/impressum"
                target="_self"
                rel="noopener">Herzog-Ernst-Gymnasium Uelzen</a
            >
        </p>
    </section>
</footer>
