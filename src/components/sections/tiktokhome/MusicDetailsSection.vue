<script setup>

defineProps({
    username:{
        type: String,
        default: 'username'
    },
    day:{
        type: String,
        default: 'day'
    },
    month:{
        type: String,
        default: 'month'
    },
    hashtag1:{
        type: String,
        default: 'hash'
    },
    hashtag2:{
        type: String,
        default: 'hash'
    },

})

</script>


<template>
    <div class="MusicDetailsSection-container">
        <div class="musicdetailselements">
            <div class="usernamendate-container">
                <a href="" class="profilename-container">
                    <span class="username">
                        @{{ username }}&nbsp;
                    </span>
                </a>
                <div class="dot-container">
                    <span class="dot">.</span>
                </div>
                <div class="date-container">
                    <span class="date">&nbsp;{{ day }}-{{ month }}</span>
                </div>
            </div>
            <div class="hashtag-container">
                <div class="hashtagitems">
                    <a href="" class="hashtaglink">
                        <span class="hashtag">
                            #{{ hashtag1 }}&nbsp; 
                        </span>
                    </a>
                    <a href="" class="hashtaglink">
                        <span class="hashtag">
                            #{{ hashtag2 }} 
                        </span>
                    </a>
                </div>
            </div>
            <div class="musicbanner-container">
                <div class="hashtagitems">
                    <div class="musicicon-container">
                        <img src="@\assets\images\svgs\musicicon.svg" alt="" class="musicicon">
                    </div>
                    <a href="" class="musiclink">
                       <span class="musictitle">
                        Avicii - Waiting For Love (ft.
                       </span>
                    </a>
                </div>
            </div>
        </div>
       
       
    </div>
    
</template>



<style scoped>
.MusicDetailsSection-container{
    display: flex;
    margin-left: 12px ;
}
.musicicon-container{
    align-items: center;
    justify-content: center;
    margin-right: 9px;
}
.usernamendate-container{
    display: flex;
    flex-direction: row;
    height: 21px;
    align-items: center;
}
.musicdetailselements{
    display: flex;
    flex-direction: column;
}
a{
    text-decoration: none;
}
.username{
    color: #FFF;
    font-family:  Poppins;
    font-size: 17px;
    font-style: normal;
    font-weight: 600;
    line-height: normal;
}

.profilename-container{
    display: flex;
    height: 21px;
    align-items: center;
}
.dot{
    color: rgba(255, 255, 255, 0.60);
    font-family: Poppins;
    font-size: 17px;
    font-style: normal;
    font-weight: 600;
    line-height: normal;
}

.date{
    color: rgba(255, 255, 255, 0.60);
    font-family: Poppins;
    font-size: 15px;
    font-style: normal;
    font-weight: 600;
    line-height: normal;
    }

.hashtagitems{
    display: flex;
    height: 20px;
    align-items: center;
    margin-top: 8px
    ;
}
.hashtag{
    display: flex;
    flex-direction: row;
    color: #FFF;
    font-family: Poppins;
    font-size: 15px;
    font-style: normal;
    font-weight: 600;
    line-height: 19.5px; /* 130% */
}
.musictitle{
    font-family: Poppins;
    font-size: 15px;
    font-style: normal;
    font-weight: 400;
    line-height: 19.5px; /* 130% */
    background: linear-gradient(270deg, rgba(255, 255, 255, 0.00) 0%, rgba(255, 255, 255, 0.90) 5.21%, rgba(255, 255, 255, 0.90) 95.83%, rgba(255, 255, 255, 0.00) 100%, rgba(255, 255, 255, 0.00) 100%);
    background-clip: text;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}
</style>