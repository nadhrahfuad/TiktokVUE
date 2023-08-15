<script setup>

</script>


<template>
    <div class="Tiktokcode-Container">
        <button class="qrbtn">
            <div class="tiktokqr-container">
                <img src="@/assets/images/svgs/tiktokcode.svg" alt="" class="qricon">
            
                <div class="qrlabel">
                    <span class="label">
                    My TikCode
                    </span>
                </div>
        </div>
        </button>   
    </div>
    
</template>



<style scoped>
.Tiktokcode-Container{
    display: flex;
    width: 414px;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    margin-top: 183.67px;
}
button{
    border: none;
    background: none;
    cursor: pointer;
}
.tiktokqr-container{
    display: flex;
    flex-direction: column;
    align-items: center;
    
}

.qrlabel{
    display: flex;
}

.label{
    display: flex;
    margin-top: 2px;
    color: #FFF;
    text-align: center;
    font-family: Poppins;
    font-size: 12px;
    font-style: normal;
    font-weight: 700;
    line-height: normal;
}
</style>