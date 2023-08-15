<script setup>
    defineProps({
        scanlabel:{
            type: String,
            default: 'scan'
        }

    })

</script>


<template>
    <div class="Mid-Container">
        <div class="cam-container">
            
        </div>
        <div class="scannerlabel">
            <span class="label">
                {{ scanlabel }}
            </span>
        </div>
       
       
    </div>
    
</template>



<style scoped>
.Mid-Container{
    display: flex;
    width: 414px;
    margin-top: 230px;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}

.cam-container{
    display: flex;
    width: 250px;
    height: 250px;
    background-image: url('@/assets/images/svgs/scanner.svg')
   
}

.scannerlabel{
    display: flex;
    margin-top:15px;
}

.label{
    color: #FFF;
    text-align: center;
    font-family: Poppins;
    font-size: 13px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
}
</style>