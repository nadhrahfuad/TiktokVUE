<!-- @/components/sections/myaccount/EditAccountSection.vue -->
<script setup>
import AllActivityHeaderOptions from '@/components/sections/allactivity/AllActivityHeaderOptions.vue'
import MidSection from '@/components/sections/allactivity/MidSection.vue';
import BottomNavigationBlack from '@/components/navigations/BottomNavigationBlack.vue'
</script>


<template>
    <div class="allactivitycontainer">
        <AllActivityHeaderOptions/>
        <div class="midsectioncontent">
            <img src="@/assets/images/svgs/notifsicon.svg" alt="" class="notifsicon">
            <MidSection heading="Notifications aren’t available" subheading="Notifications about your account will appear here"/>
        </div>
        <div class="bottomnav">
            <BottomNavigationBlack/>
        </div>
       
    </div>
</template>


<style scoped>

.allactivitycontainer{
    display: flex;
    width: 100%;
    flex-direction: column;
}

.midsectioncontent{
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 206.5px;
}

.bottomnav{
    display: flex;
    margin-top: 380.33px;
}

</style>