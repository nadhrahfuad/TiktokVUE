<script setup>

</script>


<template>
    <div class="VideoSelection-Container">
        <div class="videoselectionitems">
            <div class="viditem">
                <img src="@\assets\images\pictures\upload1.png" alt="" class="select">
            </div>

            <div class="viditemcenter">
                <img src="@\assets\images\pictures\upload2.png" alt="" class="select">
            </div>

            <div class="viditem3">
                    
            </div>
        </div>
    </div>

    
</template>



<style scoped>

.VideoSelection-Container{
    display: flex;
    width: 100%;
    overflow:hidden;
}

.videoselectionitems{
    display: flex;
    align-items: center;
    justify-content: center;
    
}

.viditemcenter{
    display: flex;
    margin-left: 33px;
    margin-right: 33px;
}

.viditem3{
    display: flex;
    width: 235px;
    height: 394px;
    flex-shrink: 0;
    border-radius: 6px;
    background: radial-gradient(50% 50.00% at 50% 50.00%, #161617 0%, #242422 100%);
    box-shadow: 0px 2.5px 2px 0px rgba(255, 255, 255, 0.10), 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
}
</style>