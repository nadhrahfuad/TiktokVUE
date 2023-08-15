<script setup>
import WhiteContainer from '@/components/container/WhiteContainer.vue';
import HomeHeader from '@/components/elements/HomeHeader.vue';
import CameraContent from '@/components/content/CameraContent.vue';
import WhiteSlider from '@/components/elements/SliderWhite.vue';
</script>

<template>
    <WhiteContainer class="bg">
       <HomeHeader currenttime="9:41"/>
       <CameraContent/>
       <WhiteSlider/>
    </WhiteContainer>
</template>


<style scoped>
.bg{
    background: #000;
}
</style>