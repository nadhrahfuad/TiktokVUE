<!-- @/components/sections/myaccount/EditAccountSection.vue -->
<script setup>


import ShareToTitleSection from '@/components/sections/shareto/ShareToTitleSection.vue'
import ShareToSection from '@/components/sections/shareto/ShareToSection.vue'
import CancelSection from '@/components/sections/shareto/CancelSection.vue'
</script>


<template>
    <div class="sharetocontent-container">
        <ShareToTitleSection title="Share to"/>
        <ShareToSection/>
        <div class="cancel-bg">
            <CancelSection/>
        </div>
    </div>
</template>


<style scoped>

.sharetocontent-container{
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 414px;
    border-radius: 8px 8px 0px 0px;
    background: #F5F5F4;
    margin-top: 499px;
}

.cancel-bg{
    display: flex;
    margin-top: 32px;
    background: #FFF;
    box-shadow: 0px -0.33000001311302185px 0px 0px #D0D1D3;
    width: 414px;
    height: 82.67px;

}


</style>