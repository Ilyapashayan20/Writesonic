<template>
    <div class="w-container relative  max-w-7xl mx-auto px-24 w-full pt-12 pb-9 flex justify-center flex-col lg:px-4  md:mx-0">
        <div class="relative min-h-[640px] lg:min-h-0 lg:pb-20 flex flex-col justify-start items-center pt-16 bg-cover px-5 bg-bottom rounded-[48px] bg-[#111827] bg-feature-hero-2">
            <h2 class="lg:text-4xl xl:text-2xl xl:mb-4  text-white mb-4 text-center text-[54px]  tracking-[-0.01em] font-bold leading-[68px]">Ready to write at&nbsp;the speed of&nbsp;light?</h2>
            <p class="text-[#ffffffcc] xl:hidden xl:text-xs mb-10 text-[18px] text-center mt-0 ">See how easy it can be&nbsp;to&nbsp;write&nbsp;amazing content.</p>
            <Button class="bg-[#ff76df] hover:bg-[#ff97e7] text-xl" title="Get Started for Free" />
            <div class="block-banner-icon absolute top-auto h-[360px] left-0 right-0 bottom-0 lg:hidden ">
                <img class="image-banner border-[#ffffff1a] absolute left-0 top-auto right-0 bottom-0 h-[317px] mx-auto pt-3 px-3 border rounded-t-[44px]" src="https://uploads-ssl.webflow.com/627a1044a798e6627445c8d1/627a1045a798e652e045c98b_content.png" loading="lazy" alt="" srcset="https://uploads-ssl.webflow.com/627a1044a798e6627445c8d1/627a1045a798e652e045c98b_content-p-500.png 500w, https://uploads-ssl.webflow.com/627a1044a798e6627445c8d1/627a1045a798e652e045c98b_content-p-800.png 800w, https://uploads-ssl.webflow.com/627a1044a798e6627445c8d1/627a1045a798e652e045c98b_content.png 1717w" sizes="(max-width: 991px) 100vw, (max-width: 1439px) 80vw, 847.875px">
                <div class="relative w-full mx-auto max-w-[900px] h-[360px]">
                    <img  v-motion-pop-visible class=" absolute left-[15%] top-5 right-auto bottom-auto" src="https://uploads-ssl.webflow.com/627a1044a798e6627445c8d1/627a1045a798e6412445c9ee_landing.png" loading="lazy" width="55.5">
                    <img v-motion-slide-visible-top class=" absolute left-auto top-[-5%]  right-0 max-h-[156px] bottom-auto" src="	https://uploads-ssl.webflow.com/627a1044a798e6627445c8d1/62f3862888c0c37a980564f0_Feature-card.png" loading="lazy" width="251.5">
                    <img  v-motion-roll-visible-left class=" w-14  absolute left-0 top-[55%] right-auto bottom-0" src="https://uploads-ssl.webflow.com/627a1044a798e6627445c8d1/627a1045a798e6621945c97d_rose-molniya.png" loading="lazy">
                </div>
            </div>
        </div>
    </div>
</template>
<script setup>
import Button from '../tools/Button.vue';
import { useMotions } from '@vueuse/motion'
useMotions
</script>
<style>
.image-banner{
    background-image: linear-gradient(180deg,rgba(145,142,255,.2),rgba(202,245,255,.07));
}
</style>