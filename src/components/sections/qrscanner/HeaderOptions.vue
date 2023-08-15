<script setup>

</script>


<template>
    <div class="Options-Container">
        <div class="optionselements">
            <div class="leftarrow-container">
                <img src="@\assets\images\svgs\leftarrowwhiteicon.svg" alt="" class="leftarrowicon">
            </div>
            <div class="scanbtn-container">
                <button class="scan">
                    <span class="scanlabel">
                        Scan
                    </span>
                </button>
            </div>
            <div class="photosbtn-container">
                <button class="photos">
                    <span class="photoslabel">
                        Photos
                    </span>
                </button>
            </div>
            
        </div>
       
       
    </div>
    
</template>



<style scoped>
.Options-Container{
    display: flex;
    height: 44px;
    width: 100%;
    align-items: center;
    margin-top: 13px;
}

.optionselements{
    display: flex;
    flex-direction: row;
    margin-left: 18px;
    margin-right: 8px;
    width: 100%;
    justify-content: space-between;
    margin-top: 13px;
    align-items: center;
}

button{
    border: none;
    background: none;
    cursor: pointer;
}
.scanlabel{
    color: #FFF;
    text-align: center;
    font-family: Poppins;
    font-size: 16px;
    font-style: normal;
    font-weight: 600;
    line-height: normal;
    letter-spacing: -0.3px;
}

.photoslabel{
    color: #FFF;
    text-align: center;
    font-family: Poppins;
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
}
</style>