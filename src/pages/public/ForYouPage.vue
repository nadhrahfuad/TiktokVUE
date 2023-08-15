<script setup>
import WhiteContainer from '@/components/container/WhiteContainer.vue';
import HomeHeader from '@/components/elements/HomeHeader.vue';
import FollowingOption from '@/components/sections/foryou/FollowingOption.vue';
import TiktokForYouContent from '@/components/content/TiktokForYouContent.vue';
import BottomNavigation from '@/components/navigations/BottomNavigation.vue';
import WhiteSlider from '@/components/elements/SliderWhite.vue';
</script>

<template>
    <WhiteContainer class="bg">
       <HomeHeader currenttime="9:41"/>
       <FollowingOption/>
       <TiktokForYouContent/>
       <BottomNavigation/>
       <WhiteSlider/>
    </WhiteContainer>
</template>


<style scoped>
.bg{
    background-image: url('@/assets/images/pictures/foryoubg.png');
    background-repeat: no-repeat;
   
}
</style>