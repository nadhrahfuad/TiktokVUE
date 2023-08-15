<!-- @/components/sections/myaccount/EditAccountSection.vue -->
<script setup>

// defineProps({
//     itemname: {
//         type: String,
//         default: 'Product name here'
//     },

//     currency: {
//         type: String,
//         default: 'currency'
//     },

//     price: {
//         type: String,
//         default: 'price'
//     },

//     oldprice: {
//         type: String,
//         default: 'oldprice'
//     },

//     sold: {
//         type: String,
//         default: 'sold'
//     },
// })


// import EditAccountSection from '@/components/sections/myaccount/EditAccountSection.vue'
// import DigitalPurchases from '@/components/sections/myaccount/DigitalPurchases.vue'
// import MyPurchasesOrange from '@/components/sections/myaccount/MyPurchasesOrange.vue'
// import EmptyContainerSection from '@/components/sections/myaccount/EmptyContainer.vue'
import RightOptions from '@/components/sections/foryou/RightOptions.vue'
import MusicDetailsSection from '@/components/sections/foryou/MusicDetailsSection.vue'
</script>


<template>
    <div class="homecontainer">
        <div class="headerbar">
                <RightOptions heartcount="328.7K" commentcount="65784"/>          
        </div>
        <MusicDetailsSection class="music" username="craig_love" date="" hashtag1="fyp" hashtag2="satisfying" hashtag3="roadmarking"  />
    </div>
</template>


<style scoped>

.homecontainer{
    display: flex;
    width: 100%;
    flex-direction: column;
}
.headerbar{
    display: flex;
    width: 100%;
    justify-content:right;
    margin-top: 310px;
}

.music{
    margin-bottom: 10px;
}

</style>