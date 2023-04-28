<script>
    let date = new Date();
    let year = date.getFullYear();
</script>

<main class="min-h-screen w-full pb-10">
    <div class="prose xl:prose-lg p-10 m-auto font-grenze prose-headings:font-gotisch">
        <img src="/favicon.png" alt="Bild Atrium" class="m-auto w-52 h-auto" />

        <header class="p-5">
            <h1 class="m-auto text-center">
                The HEGame<br /><small class="text-stone-600/70 text-xl"
                    >(coming soon!)</small
                >
            </h1>
        </header>
        <p>Wilkommen beim HEGame!</p>
        <p>
            In diesem Spiel müssen Sie sich anhand von Hinweisen durch die
            Schule bewegen, um das Spiel zu gewinnen!
        </p>
        <p>
            Das Mobile Game wird im Schulgebäude mithilfe von QR-Codes gespielt,
            sprich in Form einer Schnitzeljagd von Raum zu Raum. Diese
            Schnitzeljagd ändert sich von Durchlauf zu Durchlauf, womit
            anhaltender Spielspaß & Knobelei garantiert sind!
        </p>
        <h2>Wie kann man mitspielen?</h2>
        <p>Downloaden Sie die App im App- oder Playstore, um mitzuspielen!</p>
    </div>

    <div class="w-full mb-4 xl:mb-6 flex justify-center gap-4 items-center m-auto">
        <a href="https://play.google.com/store/apps/details?id=diepoe.heggame" target="_blank" rel="noopener"
            ><img
                class="w-48 h-auto"
                src="/badges/google-play-badge.png"
                alt="PlayStore Badge"
            /></a
        >
        <a href="/" class="cursor-not-allowed"
            ><img
                class="w-48 h-auto filter blur"
                src="/badges/Download_on_the_App_Store_Badge_DE_RGB_blk_092917.svg"
                alt="AppStore Badge"
            /></a
        >
    </div>
</main>

<footer
    class="w-full p-4 grid place-items-center border-t-2 border-t-stone-500 border-dotted"
>
    <section class="prose text-center font-grenze">
        <p class="text-primary-500">
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
        <p><b>Kontakt: hegame.app[at]heg-portal.de</b></p>
    </section>
</footer>
