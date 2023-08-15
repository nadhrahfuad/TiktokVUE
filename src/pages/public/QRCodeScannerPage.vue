<script setup>
import WhiteContainer from '@/components/container/WhiteContainer.vue';
import HomeHeader from '@/components/elements/HomeHeader.vue';
import HeaderOptions from '@/components/sections/qrscanner/HeaderOptions.vue';
import QRScannerContent from '@/components/content/QRScannerContent.vue';
import WhiteSlider from '@/components/elements/SliderWhite.vue';
</script>

<template>
    <WhiteContainer class="bg">
       <HomeHeader currenttime="9:41"/>
       <HeaderOptions/>
       <QRScannerContent/>
       <WhiteSlider/>
    </WhiteContainer>
</template>


<style scoped>
.bg{
    background-image:  url('@/assets/images/svgs/frame.svg'), url('@/assets/images/pictures/QRbg.png');
    background-repeat: no-repeat;
    
    /* background: rgba(0, 0, 0, 0.40);
    opacity: 40%; */
}
</style>