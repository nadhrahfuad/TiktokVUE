<script setup>

defineProps({
    heartcount:{
        type: String,
        default: 'heartcount'
    },
    commentcount:{
        type: String,
        default: 'commentcount'
    }
})

</script>


<template>
    <div class="TiktokRightOptions-Container">
        <div class="tiktokoptions-container">
            <div class="pfp">
                <button class="pfpbtn">
                    
                </button>
            </div>
            <div class="heart">
                <button class="heartbtn">
                    <img src="@\assets\images\svgs\hearticon.svg" alt="" class="hearticon">
                </button>
                <span class="heartcount">{{ heartcount }}</span>
            </div>
            <div class="comment">
                <button class="commentbtn">
                    <img src="@\assets\images\svgs\commenticon.svg" alt="" class="commenticon">
                </button>
                <span class="commentcount">{{ commentcount }}</span>
            </div>
            <div class="share">
                <button class="sharebtn">
                    <img src="@\assets\images\svgs\shareicon.svg" alt="" class="shareicon">
                </button>
                <span class="sharelabel">Share</span>
            </div>
            
        </div>
       
       
    </div>
    
</template>



<style scoped>
.TiktokRightOptions-Container{
    display: flex;
    width: 100%;
    
}

.tiktokoptions-container{
    display: flex;
    flex-direction: column;
    width: 100%;
    justify-content: flex-end;
    align-items: flex-end;
    margin-right: 4px;

}

.pfp{
    display: flex;
    background: none;
    background-color: none;
    width: 61px;
    align-items: center;
    justify-content: center;
}

.pfpbtn{
    width: 47px;
    height: 47px;
    flex-shrink: 0;
    border-radius: 47px;
    border: 1px solid #FFF;
    background: url('@/assets/images/pictures/foryoupfp.png'), lightgray 50% / cover no-repeat;
    background-size: 47px 47px;
    margin-bottom: 30px;
}

.heart, .comment, .share{
    display: flex;
    flex-direction: column;
    width: 61px;
    align-items: center;
    margin-bottom: 14px
}

button{
    border: none;
    background: none;
    cursor: pointer;
}

.heartcount, .commentcount, .sharelabel{
    color: #FFF;
    text-align: center;
    text-shadow: 1px 1px 0px rgba(0, 0, 0, 0.30);
    font-family: Poppins;
    font-size: 13px;
    font-style: normal;
    font-weight: 600;
    line-height: normal;
}

.heartcount{
    margin-bottom: 4px;
}

.commentcount{
    margin-bottom: 15px;
}

/* .sharelabel{
    margin-bottom: 20px;
} */


</style>