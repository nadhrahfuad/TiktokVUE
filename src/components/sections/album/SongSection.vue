<script setup>

defineProps({
    title:{
        type: String,
        default: 'songtitle'
    },
    artist:{
        type: String,
        default: 'artist'
    },
    vidcount:{
        type: String,
        default: 'vidcount'
    },
})

</script>


<template>
    <div class="Song-Container">
        <div class="songelements">
            <div class="songname-container">
                <span class="songname">
                    {{ title }}
                </span>
            </div>
            <div class="artist-container">
                <span class="artistname">
                    {{ artist }}
                </span>
            </div>
            <div class="vidcount-container">
                <span class="vidcount">
                    {{ vidcount }} videos
                </span>
            </div>
            <button class="addtofavsbtn">
                <div class="addtofavsbtnelements">
                    <div class="saveicon-container">
                        <img src="@/assets/images/svgs/saveicon.svg" alt="" class="saveicon">
                    </div>
                    <div class="savelabel">
                        <span class="label">
                            Add to Favorites
                        </span>
                    </div>
                </div>
            </button>
        </div>
       
       
    </div>
    
</template>



<style scoped>

.Song-Container{
    display: flex;
    flex-direction: column;
    margin-top: 35px;

}

button{
    border: none;
    background-color: none;
    cursor: pointer;
    background: none;
}

.songname{
    color: #161722;
    font-family: Poppins;
    font-size: 20px;
    font-style: normal;
    font-weight: 600;
    line-height: normal;
}

.artistname, .vidcount{
    color: #86878B;
    font-family: Poppins;
    font-size: 13px;
    font-style: normal;
    font-weight: 400;
    line-height: normal; 
}

.addtofavsbtn{
    display: flex;
    justify-content: center;
    align-items: center;
    width: 152px;
    height: 28px;
    border-radius: 2px;
    border: 1px solid #E3E3E4;
    margin-top: 25px;
}

.addtofavsbtnelements{
    display: flex;
    width: 152px;
    margin-left: 18px;
    margin-right: 10px;
    justify-content: space-between;
    

}

.saveicon-container{
    display:flex;
    align-items: center;
    justify-content:center;
   
}
</style>