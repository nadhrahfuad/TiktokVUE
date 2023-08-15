<!-- @/components/sections/myaccount/EditAccountSection.vue -->
<script setup>


import TopSlider from '@/components/sections/camera/TopSlider.vue'
import OptionsBar from '../sections/camera/OptionsBar.vue';
import RightSideOptions from '@/components/sections/camera/RightSideOptions.vue'
import BottomOptions from '@/components/sections/camera/BottomOptions.vue'
import FooterSliderOptions from '@/components/sections/camera/FooterSliderOptions.vue'

</script>


<template>
    <div class="cameracontent-container">
        <TopSlider/>
        <OptionsBar/>
        <RightSideOptions/>
        <BottomOptions/>
        <FooterSliderOptions/>
    </div>
</template>


<style scoped>

.cameracontent-container{
    display: flex;
    flex-direction: column;
    height: 100%;
    background-image: url('@/assets/images/pictures/camerabg.png');
    background-repeat: no-repeat;
    margin-top: 7px;;
    width: 414px;
    height: 756px;
    flex-shrink: 0;
    border-radius: 12px;
   
}



</style>