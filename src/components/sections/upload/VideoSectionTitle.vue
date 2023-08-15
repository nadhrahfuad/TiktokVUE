<script setup>

defineProps({
    year:{
        type: String,
        default: 'year'
    }
})

</script>


<template>
    <div class="VideoSectionTitle-Container">
        <div class="videotitleelements">
            <div class="title-container">
                <span class="year">
                    My {{ year }}
                </span> 
            </div>
            <div class="subtitle-container">
                <span class="uploadsubtitle">
                    Upload up to 8 photos
                </span> 
            </div>
            
        </div>
       
       
    </div>
    
</template>



<style scoped>
.VideoSectionTitle-Container{
    display: flex;
    width: 100%;
    justify-content: center;
    margin-bottom: 16px;
}

.videotitleelements{
    display: flex;
    flex-direction: column;
    align-items: center;
}

.year{
    color: #FFF;
    text-align: center;
    text-shadow: 0px 0.33000001311302185px 4px rgba(0, 0, 0, 0.20);
    font-family: Poppins;
    font-size: 24px;
    font-style: normal;
    font-weight: 700;
    line-height: normal; 
}

.uploadsubtitle{
    color: #FFF;
    text-align: center;
    text-shadow: 0px 0.33000001311302185px 4px rgba(0, 0, 0, 0.20);
    font-family: Poppins;
    font-size: 15px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    letter-spacing: -0.6px;
    opacity: 0.6;
}
</style>