<script setup>

import Separator from '@/components/elements/Separator.vue'



</script>


<template>
    <div class="shareto-container">
        <div class="sharetoelements">
            <div class="topoptions">
                <div class="whatsapp">
                    <button class="whatsapp-container">
                        <img src="@/assets/images/svgs/whatsappicon.svg" alt="" class="whatsappicon">
                    </button>
                    <div class="label-container">
                        <span class="label">
                            WhatsApp
                        </span>
                    </div>
                </div>

                <div class="whatsappstatus">
                    <button class="whatsappicon-container">
                        <img src="@/assets/images/svgs/whatsappicon.svg" alt="" class="whatsappicon">
                    </button>
                    <div class="label-container">
                        <span class="label">
                            WhatsApp status
                        </span>
                    </div>
                </div>

                <div class="message">
                    <button class="message-container">
                        <img src="@/assets/images/svgs/messageicon.svg" alt="" class="messageicon">
                    </button>
                    <div class="label-container">
                        <span class="label">
                            Message
                        </span>
                    </div>
                </div>

                <div class="SMS">
                    <button class="SMS-container">
                        <img src="@/assets/images/svgs/SMSicon.svg" alt="" class="SMSicon">
                    </button>
                    <div class="label-container">
                        <span class="label">
                            SMS
                        </span>
                    </div>
                </div>

                <div class="messenger">
                    <button class="messenger-container">
                        <img src="@/assets/images/svgs/SMSicon.svg" alt="" class="SMSicon">
                    </button>
                    <div class="label-container">
                        <span class="label">
                            Messenger
                        </span>
                    </div>
                </div>

                <div class="instagram">
                    <button class="instagram-container">
                        <img src="@/assets/images/svgs/instagramicon.svg" alt="" class="instagramicon">
                    </button>
                    <div class="label-container">
                        <span class="label">
                            Instagram
                        </span>
                    </div>
                </div>
            </div>

            <Separator class="separator"/>

            <div class="bottomoptions">
                <div class="report">
                    <button class="reporticon-container">
                        <img src="@/assets/images/svgs/reporticon.svg" alt="" class="reporticon">
                    </button>
                    <div class="abel-container">
                        <span class="label">
                            Report
                        </span>
                    </div>
                </div>

                <div class="notinterested">
                    <button class="notinterestedicon-container">
                        <img src="@/assets/images/svgs/notinterestedicon.svg" alt="" class="notinterestedicon">
                    </button>
                    <div class="label-container">
                        <span class="label">
                            Not interested
                        </span>
                    </div>
                </div>

                <div class="save">
                    <button class="save-container">
                        <img src="@/assets/images/svgs/downloadicon.svg" alt="" class="downloadicon">
                    </button>
                    <div class="label-container">
                        <span class="label">
                            Save video
                        </span>
                    </div>
                </div>

                <div class="duet">
                    <button class="duet-container">
                        <img src="@/assets/images/svgs/dueticon.svg" alt="" class="dueticon">
                    </button>
                    <div class="label-container">
                        <span class="label">
                            Duet
                        </span>
                    </div>
                </div>

                <div class="react">
                    <button class="react-container">
                        <img src="@/assets/images/svgs/reacticon.svg" alt="" class="reacticon">
                    </button>
                    <div class="label-container">
                        <span class="label">
                            React
                        </span>
                    </div>
                </div>

                <div class="favourites">
                    <button class="favourites-container">
                        <img src="@/assets/images/svgs/addtofavsicon.svg" alt="" class="addtofavsicon">
                    </button>
                    <div class="label-container">
                        <span class="label">
                            Add to Favorites
                        </span>
                    </div>
                </div>

                
            </div>
        </div>
    </div>
    
</template>



<style scoped>
.shareto-container{
    display: flex;
    width: 100%;
    justify-content: center;
}

.sharetoelements{
    display: flex;
    flex-direction: column;
    margin-left: 17px;

}

.topoptions{
    height: 82px;
    width: 393px;
    justify-content: space-between;
}

.bottomoptions{
    height: 58px;
    width: 393px;
    justify-content: space-between;
}

.topoptions, .bottomoptions{
    display:flex;
    flex: row;
}

button{
    border: none;
    background: none;
    background-color: none;
    cursor: pointer;
}

.label-container{
    display:flex;
    align-items:center;
}

.label{
    color: #4E4F57;
    text-align: center;
    font-family: Poppins;
    font-size: 11px;
    font-style: normal;
    font-weight: 400;
    line-height: normal; 
}

.whatsapp, .whatsappstatus, .message, .SMS, .messenger, .instagram{
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 50px;

}

.message-container{
    display:flex;
    width: 49px;
    height: 49px;
    align-items: center;
    justify-content:center;
    border-radius: 50%;
    background-color: #EA4359;
}

.report, .notinterested, .save, .duet, .react, .favourites{
    display: flex;
    flex-direction: column;
    align-items: center;
    height: 85px;
    width: 49px;
}

.reporticon-container, .notinterestedicon-container, .save-container, .duet-container, .react-container, .favourites-container{
    display: flex;
    align-items: center;
    justify-content: center;
    width: 47px;
    height: 47px;
    border-radius: 50%;
    background-color: #E8E8E7;
}

.separator{
    margin-top: 2px;
    margin-bottom:9px;
}
</style>