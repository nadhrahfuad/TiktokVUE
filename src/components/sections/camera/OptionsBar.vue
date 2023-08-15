<script setup>

</script>


<template>
    <div class="Options-Container">
        <div class="optionselements">
            <button class="close-container">
                <img src="@\assets\images\svgs\closeicon.svg" alt="" class="closeicon">
            </button>
            <div class="sound-container">
                <div class="soundelements">
                    <div class="soundicon">
                        <img src="@\assets\images\svgs\doubletonemusicicon.svg" alt="" class="doubletonemusicicon">
                    </div>
                    <div class="label-container">
                        <span class="label">
                            Sound
                        </span>
                    </div>
                </div>
            </div>
            
        </div>
       
       
    </div>
    
</template>



<style scoped>
.Options-Container{
    display: flex;
    height: 20px;
    width: 100%;
    align-items: center;

}

button{
    background: none;
    border: none;
    cursor: pointer;
}

.optionselements{
    display: flex;
    flex-direction: row;
    margin-left: 17.79px;
    margin-right: 17.4px;
    width: 100%;
    justify-content: space-between;
    margin-top: 29.5px;
    align-items: center;
}

.sound-container{
    display: flex;
    flex-direction: row;
    width: 240px;
}

.soundicon{
    display: flex;
    align-items: center;
}

.soundelements{
    display: flex;
    width: 64px;
    align-items: center;
    justify-content: space-between;
}

.label{
    color: #FFF;
    text-align: center;
    font-family: Poppins;
    font-size: 13px;
    font-style: normal;
    font-weight: 700;
    line-height: normal;
}
</style>