<script setup>
import WhiteContainer from '@/components/container/WhiteContainer.vue';
import HomeHeaderBlack from '@/components/elements/HomeHeaderBlack.vue';
import AllActivityContent from '@/components/content/AllActivityContent.vue';
import BlackSlider from '@/components/elements/SliderBlack.vue';
</script>

<template>
    <WhiteContainer class="bg">
       <HomeHeaderBlack currenttime="9:41"/>
       <AllActivityContent/>
       <BlackSlider/>
    </WhiteContainer>
</template>


<style scoped>
.bg{
    background: #FFF;
    border: 1px solid black;
}
</style>