<!-- @/components/sections/myaccount/EditAccountSection.vue -->
<script setup>
import SongSection from '@/components/sections/album/SongSection.vue';
import GridContainerSection from '@/components/sections/album/GridContainerSection.vue';
import AlbumPinkButton from '@/components/sections/album/AlbumPinkButton.vue'

</script>


<template>
    <div class="albumcontent-container">
        <div class="songsection">
            <div class="albumphoto">
                <button class="playbtn">
                    <img src="@/assets/images/svgs/playicon.svg" alt="" class="playicon">
                </button>
            </div>
            <SongSection title="The Round" artist="Roddy Roundicch" vidcount="1.7M"/>
        </div>
        <div class="album-section">
            <GridContainerSection/>
        </div>
        <div class="pinkbutton">
            <AlbumPinkButton btnlabel="Use this sound"/>
        </div>
    </div>
</template>


<style scoped>
.albumcontent-container{
    display: flex;
    width: 100%;
    flex-direction: column;
    
}

button{
    border: none;
    background-color: none;
    background: none;
    cursor: pointer;
}

.albumphoto{
    display: flex;
    width: 120px;
    height: 120px;
    align-items: center;
    justify-content: center;
    background-image: url('@/assets/images/pictures/albumcover.png');
    margin-right: 14px;
    margin-top: 44px;
    margin-left: 18px;
}
.songsection{
    display: flex;
    flex-direction: row;
    align-items: center;
}

.album-section{
    display: flex;
    margin-top: 10px;
}

.pinkbutton{
    position: absolute;
    margin-top: 734px;
    margin-left: 118px;
}



</style>