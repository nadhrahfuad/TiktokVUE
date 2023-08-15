<script setup>

defineProps({
        btnlabel:{
        type: String,
        default: 'btnlabel'
    }
})

</script>


<template>
    <div class="Pinkbtn-Container">
        <button class="pinkbtn">
            <div class="pinkbtnelements">
                <div class="cam-container">
                        <img src="@/assets/images/svgs/vidcamicon.svg" alt="" class="camicon">
                </div>
                <div class="btnlabel">
                    <span class="label">
                        {{ btnlabel }}
                    </span>
                </div>
            </div>
        </button>
       
       
    </div>
    
</template>



<style scoped>

.Pinkbtn-Container{
    display: flex;
    width: 100%;
    justify-content: center;
    
    
}

.pinkbtn{
    display: flex;
    align-items: center;
    width: 178px;
    height: 52px;
    border-radius: 26px;
    background: #EA4359;
    box-shadow: 0px 4px 8px 0px rgba(0, 0, 0, 0.30);
}

.pinkbtnelements{
    display: flex;
    height: 52px;
    margin-left: 13px;
    width: 100%;
    margin-right: 8px;
    justify-content: space-between;
    align-items: center;
    
}

button{
    border:none;
    background: none;
    background-color: none;
    cursor: pointer;
}
.label{
    color: #FFF;
    font-family: Poppins;
    font-size: 16px;
    font-style: normal;
    font-weight: 600;
    line-height: normal;
    letter-spacing: -0.25px;
}

</style>