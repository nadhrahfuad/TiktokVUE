<script setup>

defineProps({
    currenttime:{
        type: String,
        default: 'time'
    }
})

</script>


<template>
    <div class="TiktokHeader-Container">
        <div class="tiktokheaderelements">
            <div class="time">
                <span class="currenttime">
                    {{ currenttime }}
                </span>
            </div>
            <div class="statusbar">
                <img src="@\assets\images\svgs\blacksignalicon.svg" alt="" class="signalicon">
                <img src="@\assets\images\svgs\blackwifiicon.svg" alt="" class="wifiicon">
                <img src="@\assets\images\svgs\blackbatteryicon.svg" alt="" class="batteryicon">
            </div>
        </div>
       
       
    </div>
    
</template>



<style scoped>
.TiktokHeader-Container{
    width: 100%;
    display: flex;
    margin-top: 13px;
   
}

.tiktokheaderelements{
    width: 100%;
    display: flex;
    margin-left: 23.18px;
    margin-right: 16.5px;
    justify-content: space-between;
    align-items: center;
}

.statusbar{
    display: flex;
    width: 75.28px;
    justify-content: space-evenly;
    align-items: center;
    
}

.currenttime{

    color: #171717;
    text-align: center;
    font-family: Poppins;
    font-size: 15px;
    font-style: normal;
    font-weight: 600;
    line-height: normal;
    letter-spacing: -0.3px;
    }

.signalicon{
    width: 18.768px;
    height: 10.667px;
}

.wifiicon{
    width: 16.861px;
    height: 10.966px;
}

.batteryicon{
    width: 24.5px;
    height: 10.5px;
}
</style>