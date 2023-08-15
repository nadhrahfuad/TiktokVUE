<script setup>

defineProps({
    title:{
        type: String,
        default: 'commentscount'
    },
})

</script>


<template>
    <div class="sharetotitle-container">
        <div class="shareto-title">
            <span class="shareto">
                {{title}}
            </span>
        </div>
       
    </div>
    
</template>



<style scoped>
.sharetotitle-container{
    display: flex;
    flex-direction: column;
}

.shareto-title{
    margin-top: 12px;
    margin-bottom: 22px;
}

.shareto{
    color: #161722;
    text-align: center;
    font-family: Poppins;
    font-size: 13px;
    font-style: normal;
    font-weight: 600;
    line-height: normal;
}
</style>