<script setup>
import WhiteContainer from '@/components/container/WhiteContainer.vue';
import HomeHeader from '@/components/elements/HomeHeader.vue';
import CommentsContent from '@/components/content/CommentsContent.vue';
import BlackSlider from '@/components/elements/SliderBlack.vue';
</script>

<template>
    <WhiteContainer class="bg">
       <HomeHeader currenttime="9:41"/>
       <CommentsContent/>
       <BlackSlider/>
    </WhiteContainer>
</template>


<style scoped>
.bg{
    background-image: url('@/assets/images/pictures/foryoubg.png');
    background-repeat: no-repeat;
   
}
</style>