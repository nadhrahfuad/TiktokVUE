<script setup>

</script>


<template>
    <div class="AllActivityHeaderOptions-Container">
        <div class="optionselements">
            <div class="titleelements">
                <div class="title-container">
                    <span class="title">All activity</span>
                </div>
                <div class="dropdown-container">
                    <img src="@\assets\images\svgs\dropdown.svg" alt="" class="dropdownicon">
                </div>
            </div>
            <div class="sendmessage-container">
                <button class="send">
                    <img src="@\assets\images\svgs\sendicon.svg" alt="" class="sendicon">
                </button>
            </div>
            
        </div>
       
       
    </div>
    
</template>



<style scoped>
.AllActivityHeaderOptions-Container{
    display: flex;
    width: 414px;
    align-items: center;
    margin-top: 24px;
}

.optionselements{
    display: flex;
    flex-direction: row;
    width: 100%;
    justify-content: space-between;
    margin-left: 159px;
    margin-right: 12.5px;
}

.titleelements, .dropdown-container{
    display: flex;
    height: 21px;
    align-items: center;
    justify-content: center;
}

button{
    border: none;
    background: none;
    cursor: pointer;
}

.title{
    color: #161722;
    text-align: center;
    font-family: Poppins;
    font-size: 17px;
    font-style: normal;
    font-weight: 700;
    line-height: normal; 
}

</style>