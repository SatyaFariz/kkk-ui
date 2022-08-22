<script>
export default {
  data() {
    return {
      contactLink: 'https://wa.me/6282124707605'
    }
  }
}
</script>

<template>
    <header class="flex justify-between p-4 lg:px-20 py-7">
        <img src="https://uploads-ssl.webflow.com/61dff2e527e69016db378cd3/62547684c1f22a0134f063cd_callista-logo-dark.svg"/>
        <a class="uppercase font-normal" :href="contactLink" target="_blank">Enquire</a>
    </header>
    <main class="pt-20">
        <div class="lg:absolute lg:left-1/2 lg:transform lg:-translate-x-1/2 text-center pt-0 p-4">
            <h1 class="text-[14vw] lg:text-[7.3vw] font-thin leading-[1] uppercase lg:w-[1000px] text-[#15242e]">Kresna <br/> Kartika Karya</h1>
            <p class="lg:max-w-[30vw] text-center mt-[10px] mb-[30px] mx-auto font-normal text-sm">
                Dengan tim yang terdiri dari para profesional muda yang memiliki integritas dan kreativitas dalam bidangnya,
                kami berkomitmen memberikan pelayanan terbaik yang bertujuan pada kesuksesan setiap proyek agar terciptanya
                kepuasan klien.
            </p>
            <a :href="contactLink" target="_blank" class="inline-block">
                <span class="uppercase font-medium">Enquire</span>
                <img class="ml-3 inline" src="https://uploads-ssl.webflow.com/61dff2e527e69016db378cd3/62599f2afcc890357e83d01f_arrow-dark.svg" alt="arrow"/>
            </a>
        </div>
        <div class="p-4 lg:p-20 lg:pr-0 lg:pb-0 pr-0 pb-0">
            <div class="p-3 lg:p-10 rounded-tl-[50%] bg-[#f7f5ec] pr-0">
                <img class="rounded-tl-[50%]" src="https://uploads-ssl.webflow.com/61dff2e527e69016db378cd3/625966392ae0e1bd8e9f7c71_home-hero-hr.jpg" alt="imaks">
            </div>
        </div>
        <div class="lg:p-[120px] py-[70px] px-4 text-center">
            <h2 class="text-[6.5vw] lg:text-[4.4vw] text-[#314c5d] lg:mb-0 mb-2">Our Mission</h2>
            <p class="text-center leading-[1.5] font-light text-medium lg:text-xl font-[Sangbleuogsans,sans-serif]">
                Memberikan pelayanan terbaik, selalu memberikan inovasi dan menciptakan design terbaik sesuai dengan keinginan klien, 
                serta menjaga keharmonisan dan kesejahteraan tim sehingga mencapai hasil yang maksimal.
            </p>
        </div>
        <img class="max-h-[46vw] w-full" src="https://uploads-ssl.webflow.com/61dff2e527e69016db378cd3/6286bffa4218c2123adbf172_S04_38NewcastleStreet_INT_PH%20203%20Living_FINAL.jpg" alt="kd"/>
        <div class="lg:p-[120px] py-[70px] px-4">
            <div class="lg:grid lg:grid-cols-2 gap-20">
                <div class="flex items-center justify-center lg:justify-end">
                    <h2 class="text-[6.5vw] lg:text-[4.4vw] text-[#314c5d] lg:mb-0 mb-4">Our Services</h2>
                </div>
                <div>
                    <div>
                        <div class="text-sm lg:text-[1.5vw] font-medium mb-1">Architectural Design</div>
                        <p class="leading-[1.5] font-light text-sm lg:text-base mb-[24px] font-[Sangbleuogsans,sans-serif]">
                            Kami memberikan desain bangunan yang sesuai dengan keinginan klien. 
                            Desain bangunan merupakan gambar yang siap digunakan untuk membangun suatu bangunan.
                        </p>
                    </div>

                    <div class="ml-14 lg:ml-0">
                        <div class="text-sm lg:text-[1.5vw] font-medium mb-1">Interior Design</div>
                        <p class="leading-[1.5] font-light text-sm lg:text-base mb-[24px] font-[Sangbleuogsans,sans-serif]">
                            Kami memberikan desain Interior Ruang yang sesuai dengan keinginan klien. 
                            Desain Interior merupakan gambar yang siap digunakan untuk mengatur atau mengkonfigurasi tata letak perabot.
                        </p>
                    </div>

                    <div class="ml-4 lg:ml-0">
                        <div class="text-sm lg:text-[1.5vw] font-medium mb-1">Design Build</div>
                        <p class="leading-[1.5] font-light text-sm lg:text-base mb-[24px] font-[Sangbleuogsans,sans-serif]">
                            Kami dapat membantu untuk merealisasikan desain hingga terbangun. 
                            Kami membantu pemilik bangunan dari awal hingga projek tersebut selesai.
                        </p>
                    </div>
                </div>
                
            </div>
<!--             
            <a :href="contactLink" target="_blank" class="inline-block">
                <span class="uppercase font-medium">Enquire</span>
                <img class="ml-3 inline" src="https://uploads-ssl.webflow.com/61dff2e527e69016db378cd3/62599f2afcc890357e83d01f_arrow-dark.svg" alt="arrow"/>
            </a> -->
        </div>

        <div class="lg:p-[120px] py-[70px] px-4 bg-[#f7f5ec]">
            <div class="lg:grid lg:grid-cols-2 gap-20">
                <div class="flex items-center lg:justify-center lg:justify-end">
                    <h2 class="text-[6.5vw] lg:text-[4.4vw] text-[#314c5d] lg:mb-0 mb-4">Preliminary Stages</h2>
                </div>
                <div>
                    <div>
                        <div class="text-sm lg:text-[1.5vw] font-medium mb-1">Appointment</div>
                        <p class="leading-[1.5] font-light text-sm lg:text-base mb-[24px] font-[Sangbleuogsans,sans-serif]">
                            Anda dapat menghubungi kami dan menjadwalkan waktu yang tepat untuk bertemu dan
                            membahas rencana pekerjaan yang dilakukan.
                        </p>
                    </div>

                    <div>
                        <div class="text-sm lg:text-[1.5vw] font-medium mb-1">Site Visit</div>
                        <p class="leading-[1.5] font-light text-sm lg:text-base mb-[24px] font-[Sangbleuogsans,sans-serif]">
                            Tim kami akan meninjau langsung kelapangan untuk melakukan survey dan juga pengukuran.
                        </p>
                    </div>

                    <div>
                        <div class="text-sm lg:text-[1.5vw] font-medium mb-1">Creative Process</div>
                        <p class="leading-[1.5] font-light text-sm lg:text-base mb-[24px] font-[Sangbleuogsans,sans-serif]">
                            Tim kami bersama anda akan membuat sebuah keputusan arahan desain yang akan dilaksanakan dan
                            pengumpulan referensi.
                        </p>
                    </div>

                    <div>
                        <div class="text-sm lg:text-[1.5vw] font-medium mb-1">Drawing Detail</div>
                        <p class="leading-[1.5] font-light text-sm lg:text-base mb-[24px] font-[Sangbleuogsans,sans-serif]">
                            Tim kami akan memproduksi gambar detail sesuai dengan kesepakatan yang telah dilakukan.
                            Dalam tahap ini tim kami bersama anda akan membahas projek secara bertahap untuk hasil
                            yang optimal dan maksimal.
                        </p>
                    </div>

                    <div>
                        <div class="text-sm lg:text-[1.5vw] font-medium mb-1">Design Implementation</div>
                        <p class="leading-[1.5] font-light text-sm lg:text-base mb-[24px] font-[Sangbleuogsans,sans-serif]">
                            Tim kami akan melakukan pengawasan pada pekerjaan fisik bangunan dan juga akan melaksanakan
                            pembangunan sesuai dengan arah desain yang telah disepakati.
                        </p>
                    </div>
                </div>
                
            </div>
        </div>
    </main>
    <footer class="p-4 lg:p-20 pt-[25px] pb-[30px] bg-[#15242e]">
        <div class="relative min-h-[120vw] lg:min-h-[unset] flex justify-center items-center">
            <img class="absolute w-[50vw] h-[50vw] lg:w-[27.5vw] lg:h-[27.5vw] rounded-br-[50%] left-0 top-0" src="https://uploads-ssl.webflow.com/61dff2e527e69016db378cd3/62547688e3e50d82bb3e6a05_S01.2_38%20Newcastle%20Street_EXT_Vignette_Final-p-800.jpeg" alt="test"/>

            <img class="absolute w-[50vw] h-[50vw] lg:w-[27.5vw] lg:h-[27.5vw] rounded-tl-[50%] right-0 top-[70vw] lg:top-[5.5vw]" src="https://uploads-ssl.webflow.com/61dff2e527e69016db378cd3/6254768f1d796259ed2119cf_S18.1_38NewcastleStreet_EXT_103Backyard_Final-p-800.jpeg" alt="ks">

            <h1 class="text-center lg:text-[7.25vw] text-[14vw] leading-[1] z-99 lg:top-[2vw] relative text-white uppercase font-thin">
                Kresna
                <br/>
                Kartika
                <br/>
                Karya
            </h1>
        </div>

        <div class="lg:mt-[170px] mt-[25px] pb-[45px]">
            <div class="flex justify-center lg:gap-[2.5rem] gap-x-[12px] gap-y-[16px] flex-wrap">
                <a class="text-white font-light">
                    Outside
                </a>
                <a class="text-white font-light text-base">
                    Interior
                </a>
                <a class="text-white font-light text-base">
                    Location
                </a>
                <a class="text-white font-light text-base">
                    Video
                </a>
                <a class="text-white font-light text-base">
                    Team
                </a>
                <a class="text-white font-light text-base" :href="contactLink" target="_blank">
                    Enquire
                </a>
            </div>
        </div>

        <div class="lg:grid lg:grid-cols-3 flex flex-col gap-y-[36px]">
            <div class="flex flex-col justify-end lg:items-start">
                <p class="text-[#94a3b8] text-xs mb-[3px] text-center">Branding and Marketing by</p>
                <h4 class="text-white text-xs text-center">KKK ARCHITECT</h4>
            </div>
            <div class="flex justify-center items-end order-[-1] lg:order-[unset]">
                <a class="text-[#94a3b8] text-base font-light" href="#top">Back to top</a>
            </div>
            <div class="flex flex-col justify-end lg:items-end">
                <p class="text-[#94a3b8] text-xs mb-[3px] text-center">© {{ new Date().getFullYear() }} Kresna Kartika Karya — All rights reserved</p>
                <h4 class="text-white text-xs text-center">Architectural images are artist impressions</h4>
            </div>
        </div>
    </footer>
</template>
