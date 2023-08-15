<script setup>
import WhiteContainer from '@/components/container/WhiteContainer.vue';
import HomeHeaderBlack from '@/components/elements/HomeHeaderBlack.vue';
import OptionsBar from  '@/components/sections/album/OptionsBar.vue';
import AlbumContent from '@/components/content/AlbumContent.vue';
import BlackSlider from '@/components/elements/SliderBlack.vue';
</script>

<template>
    <WhiteContainer class="bg">
       <HomeHeaderBlack currenttime="9:41"/>
        <OptionsBar/>
        <AlbumContent/>
       <BlackSlider/>
    </WhiteContainer>
</template>


<style scoped>
.bg{
    background: #FFF;
    box-shadow: 0px 0.33000001311302185px 0px 0px #E3E3E4;  
}
</style>