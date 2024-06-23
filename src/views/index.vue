<script>
import Layout from "../layout/index.vue";
import { CountTo } from "vue3-count-to";
export default {
    name: "INDEX",
    components: {
        Layout , CountTo
    },
    mounted() {
        document.documentElement.setAttribute("dir", "ltr")
        document.documentElement.classList.add("scroll-smooth")
    }
}
</script>

<template>
        <Layout>
            <section class="pt-[100px] relative overflow-hidden" id="home">
                    <div class="container">
                        <div class="grid grid-cols-1">
                            <div class="flex flex-col flex-wrap items-center gap-5 lg:flex-row">
                                <div class="w-full lg:w-1/2">
                                    <div class="py-16 md:py-24" data-aos="fade-up">
                                        <p class="text-warning bg-warning/[14%] font-semibold text-lg inline-block p-2.5">Hi! I'm Mitchell Hancock</p>
                                        <h1 class="mt-6 md:mt-8 font-bold text-3xl/normal md:text-[50px]/normal">生産管理部 開発支援チーム</h1>
                                        <p class="text-gray mt-6 max-w-[571px] leading-loose">フィギュア業界10年、飽き性の私がこんなに続いているのは奇跡だと思っておりますが、やはり「かわいい」「カッコイイ」「感動的な造形美」はフィギュアの醍醐味であり魅了されているのだと思います。また、幼少期から培った感性を開発支援を通じてフィギュア製造に役立っていること自体も奇跡に思います。</p>
                                        <div class="flex flex-wrap gap-5 mt-10">
                                        </div>
                                        <div class="flex flex-wrap items-center gap-5 pt-12 md:pt-20 md:gap-12">
                                            <div class="space-y-3 text-center">
                                                <p class="text-2xl font-semibold" data-vanilla-counter data-start-at="0" data-end-at="180" data-time="1000" data-delay="0" data-format="{}+"> 
                                                    <count-to :startVal='0' :endVal='180' :duration='3000'></count-to>+
                                                </p>                                            <p class="text-gray">Worldwide Clients</p>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="bg-gradient-radial from-[#994FF5] to-[#FFC41F] max-w-[800px] md:top-[100px] lg:absolute bottom-0 ltr:right-0 rtl:left-0 lg:w-6/12 w-full">
                                    <p class="max-w-2xl mx-auto mt-5 text-5xl font-extrabold text-center text-transparent uppercase md:text-7xl lg:text-8xl bg-gradient-to-b from-white/70 bg-clip-text">Mitchell Hancock</p>
                                    <div class="">
                                        <img src="@/assets/images/main-img.png" class="inset-x-0 bottom-0 mx-auto -mt-16 lg:absolute md:mt-0" alt="">
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
            </section>
        <!-- home section -->
    
        <!-- Start About me -->
        <section class="py-16 md:py-24 border-t-2 border-gray/[12%] dark:border-white/[12%]" id="about">
            <div class="container" data-aos="fade-up">
                <div class="grid grid-cols-1">
                    <div>
                        <div class="inline-block">
                            <p class="bg-purple text-white text-sm font-semibold py-3 px-5 uppercase rounded-full flex items-center gap-2.5">
                                <span>
                                    <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                                        <path d="M4.33454 9.58362C5.35965 9.83993 6.16007 10.6403 6.41638 11.6655L7.37875 15.5149C7.45002 15.8 7.70616 16 8 16C8.29384 16 8.54998 15.8 8.62125 15.5149L9.58362 11.6655C9.83993 10.6403 10.6403 9.83993 11.6655 9.58362L15.5149 8.62125C15.8 8.54998 16 8.29384 16 8C16 7.70616 15.8 7.45002 15.5149 7.37875L11.6655 6.41638C10.6403 6.16007 9.83993 5.35965 9.58362 4.33454L8.62125 0.485071C8.54998 0.199992 8.29384 0 8 0C7.70616 0 7.45002 0.199991 7.37875 0.485071L6.41638 4.33454C6.16007 5.35965 5.35965 6.16007 4.33454 6.41638L0.485071 7.37875C0.199992 7.45002 0 7.70616 0 8C0 8.29384 0.199991 8.54998 0.485071 8.62125L4.33454 9.58362Z" fill="currentColor" />
                                    </svg>
                                </span>
                                About Me
                            </p>
                        </div>
                        <div class="mt-7">
                            <h2 class="font-semibold text-[26px]/normal">Hi! I'm Yuriko Saito</h2>
                            <p class="mt-6 text-gray">前回の自己紹介では「タイマッサージ」をお勧めし、前々回では「MBTI診断」を共有させていただきました。
                                疲労を感じたらタイマッサージ、悩みにぶち当たったらMBTIで自己理解を深めつつ、今でも両方ハマり続けています!
                                そして今回は「子供の頃ハマっていたもの」ということで、せっかくならいつか作ってみたいと思っていたウェブサイトで発表しようと初心者ですが頑張って作ってみました</p>
                        </div>
                    </div>
                </div>
                <div class="grid grid-cols-1 mt-14">
                    <div class="flex-wrap items-start sm:flex gap-7 space-y-7 sm:space-y-0">
                        <div class="space-y-2.5 font-semibold flex-1">
                            <p class="text-gray whitespace-nowrap">contact</p>
                            <p class="whitespace-nowrap">y8-saito@megahouse.co.jp</p>
                        </div>
                        <div class="space-y-2.5 font-semibold flex-1">
                            <p class="text-gray whitespace-nowrap">Phone</p>
                            <p class="whitespace-nowrap">080-7174-2037</p>
                        </div>
                        <div class="space-y-2.5 font-semibold flex-1">
                            <p class="text-gray whitespace-nowrap">Date of birth</p>
                            <p class="whitespace-nowrap">April 21, 1986</p>
                        </div>
                        <div class="space-y-2.5 font-semibold flex-1">
                            <p class="text-gray whitespace-nowrap">Recent interests</p>
                            <p class="whitespace-nowrap">wristwatch, self-help book</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- End About me -->
    </Layout>
</template>
