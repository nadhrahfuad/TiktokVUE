<script setup>
defineProps({
    current:{
        type: String,
        default: 'current'
    },
    total:{
        type: String,
        default: 'out of'
    }
})

</script>


<template>
    <div class="VideoSelectionCount-Container">
        <div class="selectioncountcontainer">
            <span class="count">
                {{ current }}/{{ total }}
            </span>
        </div>
       
       
    </div>
    
</template>



<style scoped>
.VideoSelectionCount-Container{
    display: flex;
    width: 100%;
    justify-content: center;
    margin-top: 16.5px;
}

.selectioncountcontainer{
    display: flex;
    width: 100%;
    justify-content: center;
    align-items: center;

}

.count{
    color: #FFF;
    text-align: center;
    text-shadow: 0px 0.33000001311302185px 4px rgba(0, 0, 0, 0.20);
    font-family: Poppins;
    font-size: 12px;
    font-style: normal;
    font-weight: 700;
    line-height: normal;
    opacity: 0.6;
}
</style>