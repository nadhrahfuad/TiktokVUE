<script setup>

defineProps({
  
    username:{
        type: String,
        default: 'username'
    },
    comment:{
        type: String,
        default: 'comment'
    },
    hour:{
        type: String,
        default: 'hour'
    },
    replies:{
        type: String,
        default: 'replies'
    },
    likenum:{
        type: String,
        default: 'likenum'
    },

})



</script>


<template>
    <div class="CommentsSection-container">
        <div class="comment">
            <div class="commentblocktop">
               
                <div class="right">
                    <div class="commentlements">
                        <div class="commentinfo">
                            <div class="username">
                                <span class="commentusername">@{{username}}</span>
                            </div>
                            <div class="commentconent">
                                <span class="commenttxt">{{ comment }}
                            <span class="time">&nbsp;{{hour}}</span></span>
                            </div>
                            <div class="viewrepliesdrop1">
                            <span class="replies1">
                                {{replies}}
                            </span>
                                <i class="fa-solid fa-chevron-down"></i>
                            </div>
                        </div>
                        
                    </div>
                    <div class="likecomment">
                        <img src="@\assets\images\svgs\heartsttrokeicon.svg" alt="" class="heart">
                        <span class="likenum">{{ likenum }}</span>
                    </div>
                </div>
                
            </div>
        </div>
    </div>
    
</template>



<style scoped>
.CommentsSection-container{
    display: flex;
    width: 100%;
    flex-direction: column;
    align-items: center;
}

.comment{
    display: flex;
    width: 414px;
}

.commentblocktop{
    display: flex;
    align-items: center;
    margin-left: 16px;
}

.pfp{
    margin-right:12px;
}
.likecomment{
    display: flex;
    align-items: center;
    flex-direction: column;
}

.right{
    display: flex;
    width: 345px;
    justify-content: space-between;
    align-items: center;
}

.commentusername{
    display: flex;
    color: #86878B;
    font-family: Poppins;
    font-size: 13px;
    font-style: normal;
    font-weight: 600;
    line-height: normal;
    margin-bottom:5px;
}

.commenttxt{
    display: flex;
    color: #161722;
    font-family: Poppins;
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    

}

.time{
    color: #86878B;
    font-family: Poppins;
    font-size: 13px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    margin-right: 13px
}

.replies1{
    color: #86878B;
    font-family: Poppins;
    font-size: 13px;
    font-style: normal;
    font-weight: 600;
    line-height: normal;
}

.likenum{
    color: #86878B;
    text-align: center;
    font-family: Poppins;
    font-size: 13px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
}
</style>