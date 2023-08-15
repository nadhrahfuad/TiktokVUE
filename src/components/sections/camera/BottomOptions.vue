<script setup>

</script>


<template>
    <div class="BottomOptions-Container">
        <div class="bottomoptionselements">
           <button class="effectsbtn">
                <img src="@\assets\images\svgs\effectssmileicon.svg" alt="" class="filtersmileicon">
                <div class="btnlabel">
                    <span class="label">
                        Effects
                    </span>
                </div>
           </button>

           <button class="recordbtn">
                <img src="@\assets\images\svgs\recordicon.svg" alt="" class="recordicon">
           </button>

           <button class="uploadbtn">
                <img src="@\assets\images\svgs\uploadicon.svg" alt="" class="uploadicon">
                <div class="btnlabel">
                    <span class="label">
                        Upload
                    </span>
                </div>
           </button>
           
        </div>
       
       
    </div>
    
</template>



<style scoped>
.BottomOptions-Container{
    display: flex;
    width: 100%;
    margin-top: 233px;
}

.bottomoptionselements{
    display: flex;
    align-items: center;
    flex-direction: row;
    width: 100%;
    margin-left: 66.5px;
    margin-right: 67.5px;
    justify-content: space-between;

}


button{
    border: none;
    background: none;
    cursor: pointer;
}

.label{
    color: #FFF;
    text-align: center;
    text-shadow: 0px 0.33000001311302185px 4px rgba(0, 0, 0, 0.10);
    font-family: Poppins;
    font-size: 11px;
    font-style: normal;
    font-weight: 700;
    line-height: normal;
}
</style>