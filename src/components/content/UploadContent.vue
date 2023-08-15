<!-- @/components/sections/myaccount/EditAccountSection.vue -->
<script setup>
import CloseSectionHeader from '@/components/sections/upload/CloseSectionHeader.vue'
import VideoSectionTitle from '@/components/sections/upload/VideoSectionTitle.vue'
import VideoSelection from '@/components/sections/upload/VideoSelection.vue'
import VideoSelectionCount from '@/components/sections/upload/VideoSelectionCount.vue'
import PinkButton from '@/components/sections/upload/PinkButton.vue'
import FooterSliderOptions from '@/components/sections/upload/FooterSliderOptions.vue'
</script>


<template>
    <div class="uploadcontainer">
        <CloseSectionHeader/>
        <VideoSectionTitle year="2020"/>
        <VideoSelection/>
        <VideoSelectionCount current="3" total="22"/>
        <PinkButton btnlabel="Select photos"/>
        <FooterSliderOptions/>
       
    </div>
</template>


<style scoped>

.uploadcontainer{
    display: flex;
    width: 100%;
    flex-direction: column;
}

</style>