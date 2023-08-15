<script setup>

</script>


<template>
    <div class="RightOptions-Container">
        <div class="rightoptionselements">
            <div class="flip-container">
                <div class="flipicon-container">
                    <button class="flip">
                        <img src="@\assets\images\svgs\flip.svg" alt="" class="flipicon">
                    </button>
                </div>
                <div class="btnlabel">
                    <span class="label">
                        Flip
                    </span>
                </div>
                
            </div>

            <div class="speed-container">
                <div class="speedicon-container">
                    <button class="speed">
                        <img src="@\assets\images\svgs\speed.svg" alt="" class="speedicon">
                    </button>
                </div>
                <div class="btnlabel">
                    <span class="label">
                        Speed
                    </span>
                </div>
            </div>

            <div class="beauty-container">
                <div class="beautyicon-container">
                    <button class="beauty">
                        <img src="@\assets\images\svgs\beauty.svg" alt="" class="beautyicon">
                    </button>
                </div>
                <div class="btnlabel">
                    <span class="label">
                        Beauty
                    </span>
                </div>
            </div>

            <div class="filters-container">
                <div class="filtersicon-container">
                    <button class="filters">
                        <img src="@\assets\images\svgs\filters.svg" alt="" class="filtersicon">
                    </button>
                </div>
                <div class="btnlabel">
                    <span class="label">
                        Filters
                    </span>
                </div>
            </div>

            <div class="timer-container">
                <div class="timericon-container">
                    <button class="timer">
                        <img src="@\assets\images\svgs\timer.svg" alt="" class="timericon">
                    </button>
                </div>
                <div class="btnlabel">
                    <span class="label">
                        Timer
                    </span>
                </div>
            </div>

            <div class="flash-container">
                <div class="flashicon-container">
                    <button class="flash">
                        <img src="@\assets\images\svgs\flash.svg" alt="" class="flashicon">
                    </button>
                </div>
                <div class="btnlabel">
                    <span class="label">
                        Flash
                    </span>
                </div>
            </div>
            
        </div>
       
       
    </div>
    
</template>



<style scoped>
.RightOptions-Container{
    display: flex;
    width: 100%;
    margin-top: 15px;
    justify-content: flex-end;
    flex-direction: column;

}

button{
    background:none;
    border: none;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 7.5px;
    width: 32px;
}

.rightoptionselements{
    display:flex;
    width: 399.5px;
    justify-content: flex-end;
    margin-right:14.5px;
    flex-direction: column;
    margin-top: -25px;
}

.flip-container, .speed-container, .beauty-container, .filters-container, .timer-container, .flash-container{
    display:flex;
    flex-direction: column;
    width:100%;
    align-items: flex-end;
}

.btnlabel{
    display:flex;
    width: 32px;
    align-items: center;
    justify-content: center;
    margin-bottom: 20px;
}

.btnlabel>span{
    color: #FFF;
    text-align: center;
    font-family: Poppins;
    font-size: 10px;
    font-style: normal;
    font-weight: 700;
    line-height: normal;
}
</style>