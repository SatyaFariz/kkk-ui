<script setup>
</script>

<template>
    <header class="grid grid-cols-3 px-14 py-7">
        <img src="https://uploads-ssl.webflow.com/61dff2e527e69016db378cd3/62547684c1f22a0134f063cd_callista-logo-dark.svg"/>
    </header>
    <main class="pt-20">
        <div class="absolute left-1/2 transform -translate-x-1/2 text-center">
            <h1 class="text-[7.3vw] font-thin leading-[1] uppercase w-[1000px]">Kresna <br/> Kartika Karya</h1>
            <p class="max-w-[30vw] text-center mt-[10px] mb-[30px] mx-auto font-normal text-[1.15vw]">
                One of Sydney’s most refined neighbourhoods is now home to an exclusive new development that fuses contemporary luxury with timeless design. Welcome to Callista.
            </p>
            <a href="google.com" target="_blank" class="inline-block">
                <span class="uppercase font-medium">Enquire</span>
                <img class="ml-3 inline" src="https://uploads-ssl.webflow.com/61dff2e527e69016db378cd3/62599f2afcc890357e83d01f_arrow-dark.svg" alt="arrow"/>
            </a>
        </div>
        <div class="p-20 pr-0 pb-0">
            <div class="p-10 rounded-tl-[50%] bg-[#f7f5ec] pr-0">
                <img class="rounded-tl-[50%]" src="https://uploads-ssl.webflow.com/61dff2e527e69016db378cd3/625966392ae0e1bd8e9f7c71_home-hero-hr.jpg" alt="imaks">
            </div>
        </div>
        <div class="p-[120px]">
            <p class="text-center leading-[1.5] font-light text-xl">
                From the grand entrance that sweeps you into its embrace, Callista promises something truly beguiling. Behold an enclave of 8 luxuriously appointed apartments, generously proportioned and meticulously crafted. Step inside and you’ll find Callista has cast its spell, and your destiny awaits.
            </p>
        </div>
        <img class="max-h-[46vw] w-full" src="https://uploads-ssl.webflow.com/61dff2e527e69016db378cd3/6286bffa4218c2123adbf172_S04_38NewcastleStreet_INT_PH%20203%20Living_FINAL.jpg" alt="kd"/>
        <div class="p-[120px] text-center">
            <p class="text-center leading-[1.5] font-light text-xl mb-[24px]">
                From the grand entrance that sweeps you into its embrace, Callista promises something truly beguiling. Behold an enclave of 8 luxuriously appointed apartments, generously proportioned and meticulously crafted. Step inside and you’ll find Callista has cast its spell, and your destiny awaits.
            </p>
            <a href="google.com" target="_blank" class="inline-block">
                <span class="uppercase font-medium">Enquire</span>
                <img class="ml-3 inline" src="https://uploads-ssl.webflow.com/61dff2e527e69016db378cd3/62599f2afcc890357e83d01f_arrow-dark.svg" alt="arrow"/>
            </a>
        </div>
    </main>
    <footer class="p-20 pb-[30px] bg-[#15242e]">
        <div class="relative">
            <img class="absolute w-[27.5vw] h-[352px] rounded-br-[50%]" src="https://uploads-ssl.webflow.com/61dff2e527e69016db378cd3/62547688e3e50d82bb3e6a05_S01.2_38%20Newcastle%20Street_EXT_Vignette_Final-p-800.jpeg" alt="test"/>

            <img class="absolute w-[27.vw] h-[352px] rounded-tl-[50%] right-0 top-[5.5vw]" src="https://uploads-ssl.webflow.com/61dff2e527e69016db378cd3/6254768f1d796259ed2119cf_S18.1_38NewcastleStreet_EXT_103Backyard_Final-p-800.jpeg" alt="ks">

            <h1 class="text-center text-[7.25vw] leading-[1] z-99 top-[2vw] relative text-white uppercase font-thin">
                Kresna
                <br/>
                Kartika
                <br/>
                Karya
            </h1>
        </div>

        <div class="mt-[120px] pb-[45px]">
            <div class="text-white text-center text-[1.12rem] uppercase mb-[1.5rem] font-medium">Where To?</div>
            <div class="flex justify-center gap-[2.5rem]">
                <a class="text-white font-thin">
                    Outside
                </a>
                <a class="text-white font-thin text-base">
                    Interior
                </a>
                <a class="text-white font-thin text-base">
                    Location
                </a>
                <a class="text-white font-thin text-base">
                    Video
                </a>
                <a class="text-white font-thin text-base">
                    Team
                </a>
                <a class="text-white font-thin text-base" href="#top">
                    Enquire
                </a>
            </div>
        </div>

        <div class="grid grid-cols-3">
            <div class="flex flex-col justify-end">
                <p class="text-[#94a3b8] text-xs mb-[3px]">Branding and Marketing by</p>
                <h4 class="text-white text-xs">KKK ARCHITECT</h4>
            </div>
            <div class="flex justify-center items-end">
                <a class="text-[#94a3b8] text-base font-light" href="#top">Back to top</a>
            </div>
            <div class="flex flex-col items-end justify-end">
                <p class="text-[#94a3b8] text-xs mb-[3px]">© {{ new Date().getFullYear() }} Kresna Kartika Karya — All rights reserved</p>
                <h4 class="text-white text-xs">Architectural images are artist impressions</h4>
            </div>
        </div>
    </footer>
</template>
