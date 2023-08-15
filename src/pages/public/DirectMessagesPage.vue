<script setup>
import WhiteContainer from '@/components/container/WhiteContainer.vue';
import HomeHeaderBlack from '@/components/elements/HomeHeaderBlack.vue';
import DirectMessagesContent from '@/components/content/DirectMessagesContent.vue';
import BlackSlider from '@/components/elements/SliderBlack.vue';
</script>

<template>
    <WhiteContainer class="bg">
       <HomeHeaderBlack currenttime="9:41"/>
       <DirectMessagesContent/>
       <BlackSlider/>
    </WhiteContainer>
</template>


<style scoped>
.bg{
    background: #FFF;
    border: 1px solid black;
}
</style>