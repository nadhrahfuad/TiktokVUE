<!-- @/components/sections/myaccount/EditAccountSection.vue -->
<script setup>
import CommentsTitleSection from '@/components/sections/comments/CommentsTitleSection.vue'
import CommentsSection from '@/components/sections/comments/CommentsSection.vue'
import AddCommentSection from '@/components/sections/comments/AddCommentSection.vue'

</script>


<template>
    <div class="comments-container">
        
        <CommentsTitleSection commentscount="579" />
        <div class="comment1">
            <div class="pfp">
                        <img src="@\assets\images\pictures\commentspfp.png" alt="" class="user1">
            </div>
            <CommentsSection username="martini_rond" comment="How neatly I write the date in my book" hour="22h" replies="View replies (4)" likenum="8098"/>
        </div>
        
        <div class="comment">
            <div class="pfp">
                        <img src="@\assets\images\pictures\commentspfp2.png" alt="" class="user1">
            </div>
            <CommentsSection username="maxjacobson" comment="Now that’s a skill very talented" hour="22h" replies="View replies (1)" likenum="8098"/>
        </div>

        <div class="comment">
            <div class="pfp">
                        <img src="@\assets\images\pictures\commentspfp3.png" alt="" class="user1">
            </div>
            <CommentsSection username="zackjohn" comment="Doing this would make me so anxious" hour="22h" replies="" likenum="8098"/>
        </div>

        <div class="comment">
            <div class="pfp">
                        <img src="@\assets\images\pictures\commentspfp4.png" alt="" class="user1">
            </div>
            <CommentsSection username="mkiero_d" comment="Use that on r air forces to whiten them" hour="21h" replies="View replies (9)" likenum="8098"/>
        </div>
        
        <div class="comment">
            <div class="pfp">
                        <img src="@\assets\images\pictures\commentspfp5.png" alt="" class="user1">
            </div>
            <CommentsSection username="mis_potter" comment="Sjpuld’ve used that on his forces 😷😷 " hour="13h" replies="View replies (4)" likenum="8098"/>
        </div>
        <div class="comment">
            <div class="pfp">
                        <img src="@\assets\images\pictures\commentspfp6.png" alt="" class="user1">
            </div>
            <CommentsSection username="karennne" comment="No prressure" hour="22h" replies="replies (2)" likenum="8098"/>
        </div>

        <div class="comment7">
            <div class="pfp">
                        <img src="@\assets\images\pictures\commentspfp7.png" alt="" class="user1">
            </div>
            <CommentsSection username="joshua_l" comment="My OCD couldn’t do it" hour="15h" replies="" likenum="8098"/>
        </div>

        <div class="commentsection">
            <AddCommentSection/>
        </div>
    </div>
</template>


<style scoped>

.comments-container{
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 414px;
    height: 571px;
    flex-shrink: 0;
    border-radius: 8px 8px 0px 0px;
    background: #F5F5F4;
    margin-top: 242px;
}

.comment1{
    display: flex;
    width: 100%;
    height: 80px;
    align-items: center;
    margin-left: 16px;
    margin-bottom: 11px;
}
.comment7{
    display: flex;
    width: 100%;
    height: 80px;
    align-items: center;
    margin-left: 16px;
}

.comment{
    display: flex;
    width: 100%;
    height: 80px;
    align-items: center;
    margin-left: 16px;
    margin-bottom: 11px;
}

.commentsection{
    width: 414px;
    height: 85px;
    flex-shrink: 0; 
    background-color: #FFF;
    box-shadow: 0px -0.33000001311302185px 0px 0px #D0D1D3;
}

</style>