<script setup>
import WhiteContainer from '@/components/container/WhiteContainer.vue';
import HomeHeader from '@/components/elements/HomeHeader.vue';
import UploadContent from '@/components/content/UploadContent.vue';
import WhiteSlider from '@/components/elements/SliderWhite.vue';
</script>

<template>
    <WhiteContainer class="bg">
       <HomeHeader currenttime="9:41"/>
       <UploadContent/>
       <WhiteSlider/>
    </WhiteContainer>
</template>


<style scoped>
.bg{
    background: linear-gradient(180deg, #232320 4.17%, #2D2C28 10.42%, #18181A 70.07%, #131313 100%);
}
</style>