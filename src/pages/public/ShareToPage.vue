<script setup>
import WhiteContainer from '@/components/container/WhiteContainer.vue';
import HomeHeader from '@/components/elements/HomeHeader.vue';
import FollowingOption from '@/components/sections/foryou/FollowingOption.vue';
import BlackSlider from '@/components/elements/SliderBlack.vue';
import ShareToContent from '@/components/content/ShareToContent.vue';
</script>

<template>
    <WhiteContainer class="bg">
       <HomeHeader currenttime="9:41"/>
       <FollowingOption/>
       <ShareToContent/>
       <BlackSlider/>
    </WhiteContainer>
</template>


<style scoped>
.bg{
    background-image: url('@/assets/images/pictures/foryoubg.png');
    background-repeat: no-repeat;
   
}
</style>