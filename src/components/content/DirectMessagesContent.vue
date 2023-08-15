<!-- @/components/sections/myaccount/EditAccountSection.vue -->
<script setup>
import DirectMessagesHeaderOptions from '@/components/sections/directmessages/DirectMessagesHeaderOptions.vue'
import MidSection from '@/components/sections/allactivity/MidSection.vue';
import BottomNavigationBlack from '@/components/navigations/BottomNavigationBlack.vue'
</script>


<template>
    <div class="allactivitycontainer">
        <DirectMessagesHeaderOptions/>
        <div class="midsectioncontent">
            <img src="@/assets/images/svgs/dmmessageicon.svg" alt="" class="notifsicon">
            <MidSection heading="Message your friends" subheading="Share videos or start a conversation"/>
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