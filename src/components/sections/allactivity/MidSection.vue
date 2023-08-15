<script setup>
defineProps({
    heading:{
        type: String,
        default: 'heading'
    },

    subheading:{
        type: String,
        default: 'subheading'
    },
    

})
</script>


<template>
    <div class="MidSection-Container">
        <div class="midsectionelements">
            <span class="heading">
                {{ heading }}
            </span>
            <span class="subheading">
                {{ subheading }}
            </span>
            
        </div>
       
       
    </div>
    
</template>



<style scoped>
.MidSection-Container{
    display: flex;
    width: 100%;
    margin-top: 25.15px;
}

.midsectionelements{
    display: flex;
    width: 100%;
    flex-direction: column;
}
.heading{
    color: #161722;
    text-align: center;
    font-family: Poppins;
    font-size: 17px;
    font-style: normal;
    font-weight: 700;
    line-height: normal; 
}

.subheading{
    color: #7C7D83;
    text-align: center;
    font-family: Poppins;
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
}

</style>