<script setup>

defineProps({
    currenttime:{
        type: String,
        default: 'time'
    }
})

</script>


<template>
    <div class="Following-Container">
        <div class="followingelements">
            <button class="following-container">
               <span class="following">Following</span>
            </button>
            <div class="separator">
                <img src="@\assets\images\svgs\separatoricon.svg" alt="" class="separatoricon">
            </div>
            
            <button class="foryou-container">
               <span class="foryou">For You</span>
            </button>
        </div>
       
       
    </div>
    
</template>



<style scoped>
.Following-Container{
    display: flex;
    width: 100%;
    justify-content: center;
}

.followingelements{
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    align-items: center;
    height: 44px;;
}

button{
    background: none;
    border: none;
    cursor: pointer;
}
.following{
    color: #FFF;
    text-align: center;
    font-family: Poppins;
    font-size: 16px;
    font-style: normal;
    font-weight: 600;
    line-height: normal;
}

.separatoricon{
    border:  rgba(255, 255, 255, 0.20) 1px solid;
    width: 0px;
    height: 11px;
    margin-left: 12.5px;
    margin-right: 8.5px;
}


.foryou{
    color: rgba(255, 255, 255, 0.60);
    text-align: center;
    font-family: Poppins;
    font-size: 18px;
    font-style: normal;
    font-weight: 600;
    line-height: normal;
}
</style>