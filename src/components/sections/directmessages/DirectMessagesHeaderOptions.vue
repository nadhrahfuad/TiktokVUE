<script setup>

</script>


<template>
    <div class="DirectMessagesHeaderOptions-Container">
        <div class="optionselements">
            <div class="titleelements">
                <button class="back-container">
                    <img src="@\assets\images\svgs\leftarrowblackicon.svg" alt="" class="dropdownicon">
                </button>

                <div class="title-container">
                    <span class="title">Direct messages</span>
                </div>
                
                <div class="sendmessage-container">
                    <button class="send">
                        <img src="@\assets\images\svgs\addicon.svg" alt="" class="sendicon">
                    </button>
                </div>
        </div>
            
        </div>
       
       
    </div>
    
</template>



<style scoped>
.DirectMessagesHeaderOptions-Container{
    display: flex;
    width: 414px;
    align-items: center;
    margin-top: 24px;
    
}

.optionselements{
    display: flex;
    flex-direction: row;
    width: 100%;
    margin-left: 18px;
    margin-right: 13.67px;
    box-shadow: 0px 0.33000001311302185px 0px 0px #D0D1D3;
}

.titleelements{
    display: flex;
    height: 21px;
    width: 100%;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 11.67px
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