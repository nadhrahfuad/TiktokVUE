<script setup>

defineProps({
    currenttime:{
        type: String,
        default: 'time'
    }
})

</script>


<template>
     <div class="vidgrid">
                    <div class="grid-container">
                        <div class="griditem">
                            <img src="@/assets/images/pictures/album1.png" alt="">
                        </div>
                        <div class="griditem">
                            <img src="@/assets/images/pictures/album2.png" alt="">
                        </div>
                        <div class="griditem">
                            <img src="@/assets/images/pictures/album3.png" alt="">
                        </div>
                        <div class="griditem">
                            <img src="@/assets/images/pictures/album4.png" alt="">
                        </div>
                        <div class="griditem">
                            <img src="@/assets/images/pictures/album5.png" alt="">
                        </div>
                        <div class="griditem">
                            <img src="@/assets/images/pictures/album6.png" alt="">
                        </div>
                        <div class="griditem">
                            <img src="@/assets/images/pictures/album7.png" alt="">
                        </div>
                        <div class="griditem">
                            <img src="@/assets/images/pictures/album8.png" alt="">
                        </div>
                        <div class="griditem">
                            <img src="@/assets/images/pictures/album9.png" alt="">
                        </div>
                        <div class="griditem">
                            <img src="@/assets/images/pictures/album10.png" alt="">
                        </div>
                        <div class="griditem">
                            <img src="@/assets/images/pictures/album11.png" alt="">
                        </div>
                        <div class="griditem">
                            <img src="@/assets/images/pictures/album12.png" alt="">
                        </div>
                    </div>
                </div>
    
</template>



<style scoped>
.vidgrid {
  display: flex;
  margin-top: 33.3px;
  overflow: hidden;
}

.grid-container {
  display: grid;
  /* grid-template-columns: 137px 137px 137px; */
  grid-template-rows: repeat(3, 182px);
  grid-template-columns: repeat(3, 137px);
  row-gap: 1.66px;
  column-gap: 1.33px;
  position: relative;
  /* grid-template-columns: auto auto auto; */
}

/* .griditem {
  display: flex;
} */
</style>