<script setup>

defineProps({
    commentscount:{
        type: String,
        default: 'commentscount'
    },
})

</script>


<template>
    <div class="CommentsSection-container">
        <div class="comments-title">
            <span class="commentscount">
                {{ commentscount  }} comments
            </span>
        </div>
       
    </div>
    
</template>



<style scoped>
.CommentsSection-container{
    display: flex;
    flex-direction: column;
}

.comments-title{
    margin-top: 12px;
    margin-bottom: 22px;
}

.commentscount{
    color: #161722;
    text-align: center;
    font-family: Poppins;
    font-size: 13px;
    font-style: normal;
    font-weight: 600;
    line-height: normal;
}
</style>