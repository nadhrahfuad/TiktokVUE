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
            <div class="btnlabel">
                <span class="label">
                    {{ btnlabel }}
                </span>
            </div>

        </button>
       
       
    </div>
    
</template>



<style scoped>

.Pinkbtn-Container{
    display: flex;
    width: 100%;
    justify-content: center;
    margin-top: 56.5px;
    
    
}

.pinkbtn{
    display: flex;
    align-items: center;
    width: 270px;
    height: 44px;
    flex-shrink: 0;
    border-radius: 22px;
    background: #EA4359;
}

.btnlabel{
    display: flex;
    width: 100%;
    justify-content: center;
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
    text-align: center;
    font-family: Poppins;
    font-size: 15px;
    font-style: normal;
    font-weight: 700;
    line-height: normal;
}

</style>