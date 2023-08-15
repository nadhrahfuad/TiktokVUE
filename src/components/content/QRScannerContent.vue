<!-- @/components/sections/myaccount/EditAccountSection.vue -->
<script setup>


import MidSection from '@/components/sections/qrscanner/MidSection.vue'
import TiktokCodeSection from '@/components/sections/qrscanner/TiktokCodeSection.vue'
</script>


<template>
    <div class="sharetocontent-container">
        <MidSection scanlabel="Align QR code in frame to scan"/>
        <TiktokCodeSection/>
    </div>
</template>


<style scoped>

.sharetocontent-container{
    display: flex;
    flex-direction: column;
   
}



</style>