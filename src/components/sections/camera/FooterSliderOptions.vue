<script setup>

</script>


<template>
    <div class="FooterSliderOptions-Container">
        <div class="footerslideroptionselements">
            <div class="sixtybtn-container">
                <button class="sixty">
                        <span class="label">
                            60s
                        </span>
                </button>
            </div>

            <div class="activebtn-container">
                <button class="fifteen">
                        <span class="activelabel">
                            15s
                        </span>
                </button>
                <button class="pointerbtn">
                    <img src="@\assets\images\svgs\whitedotbtn.svg" alt="" class="recordicon">
                </button>
            </div>

            <div class="templates-container">
                <button class="templates">
                        <span class="label">
                            Templates
                        </span>
                </button>
            </div>
             
        </div>
          
    </div>
    
</template>



<style scoped>
.FooterSliderOptions-Container{
    display: flex;
    width: 100%;
}

.footerslideroptionselements{
    display: flex;
    width: 100%;
    justify-content: center;
    margin-top: 20px;
}

.activebtn-container{
    display: flex;
    flex-direction: column;
    
}

.activelabel{
    color: #FFF;
    text-align: center;
    font-family: Poppins;
    font-size: 15px;
    font-style: normal;
    font-weight: 700;
    line-height: normal;
}

.sixtybtn-container, .activebtn-container, .templates-container{
    width: 70px;
}

button{
    border: none;
    background: none;
    cursor: pointer;
}

.label{
    color: #FFF;
    text-align: center;
    font-family: Poppins;
    font-size: 15px;
    font-style: normal;
    font-weight: 700;
    line-height: normal;
    opacity: 0.6;
}
</style>