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
    hashtag3:{
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
            </div>
            <div class="hashtag-container">
                <div class="captionitems">
                    <span class="caption">The most satisfying Job <span class="hash">&nbsp;#{{ hashtag1 }}</span><span class="hash">&nbsp;#{{ hashtag2 }}</span> </span>
                </div>
            </div>
            <div class="musicbanner-container">
                <div class="hashtagitems">
                    <div class="musicicon-container">
                        <img src="@\assets\images\svgs\musicicon.svg" alt="" class="musicicon">
                    </div>
                    <a href="" class="musiclink">
                       <span class="musictitle">
                        Roddy Roundicch - The Rou
                       </span>
                    </a>
                </div>
            </div>
        </div>
        <div class="musicdisc">
                <button class="musicdiscbtn">
                    <div class="musicdiscicon">
                        <img src="@\assets\images\svgs\discicon.svg" alt="" class="musicdiscicon">
                        
                    </div>
                    
                </button>
            </div>
       
       
    </div>
    
</template>



<style scoped>
.MusicDetailsSection-container{
    display: flex;
    margin-left: 12px ;
    align-items: center;
    justify-content: space-between;
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

.caption{
    display: flex;
    color: rgba(255, 255, 255, 0.90);
    font-family: Poppins;
    font-size: 15px;
    font-style: normal;
    font-weight: 400;
    line-height: 19.5px; /* 130% */
    }
.hashtagitems{
    display: flex;
    height: 20px;
    align-items: center;
    margin-top: 8px
    ;
}
.hash{
    display: flex;
    flex-direction: row;
    color: #FFF;
    font-family: Poppins;
    font-size: 15px;
    font-style: normal;
    font-weight: 600;
    line-height: 19.5px;
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
.captionitems{
    display: flex;
    flex-direction: row;
}
.musicdisc, .musicdiscbtn, .musicdiscicon{
    display: flex;
}

.musicdiscicon{
    width: 49px;
    height: 49px;
}

button{
    background: none;
    border: none;
    background-color: NONE;
    cursor: pointer;
    margin-top: 30px
}
</style>