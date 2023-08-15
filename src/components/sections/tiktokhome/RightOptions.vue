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
            <div class="music">
                <button class="musicbtn">
                    <div class="musicicon">
                        <img src="@\assets\images\svgs\musicdisc.svg" alt="" class="musicdiscicon">
                        <div class="playerpic">
                        <img src="@\assets\images\pictures\musicinner.png" alt="" class="inner">
                    </div>
                    </div>
                    
                </button>
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
    background: url('@/assets/images/pictures/hometiktokpfp.png'), lightgray 50% / cover no-repeat;
    background-size: 47px 47px;
    margin-bottom: 30px;
}

.heart, .comment, .share{
    display: flex;
    flex-direction: column;
    width: 61px;
    align-items: center;
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

.music, .musicbtn, .musicicon{
    display: flex;
}

.musicicon{
    width: 49px;
    height: 49px;
}

.playerpic{
    display: flex;
    position: absolute;
    width: 27px;
    height: 27px;
    border-radius: 50%;
    transform: rotate(133.123deg);
    margin-top: 11.42px;
    margin-left: 11.42px;
}

.inner{
    width: 27px;
    height: 27px;
    border-radius: 50%;
}
</style>