<template>
  <!-- <div>
    <router-link :to="{ name: 'SplashScreen' }">Splash</router-link> |

  </div> -->

  <!-- <router-view /> -->
  
  <TiktokHomePage/>
  <ForYouPage/>
  <CommentsPage/>
  <ShareToPage/>
  <AlbumPage/>
  <QRCodeScannerPage/>
  <CameraPage/>
  <UploadPage/>
  <AllActivityPage/>
  <DirectMessagesPage/>
</template>

<script setup>
// import router from './router';
//import ForYouPage from './pages/public/ForYouPage.vue';
//import TiktokHomePage from './pages/public/TiktokHomePage.vue'
//import CommentsPage from './pages/public/CommentsPage.vue';
//import ShareToPage from './pages/public/ShareToPage.vue';
//import AlbumPage from './pages/public/AlbumPage.vue';
//import QRCodeScannerPage from './pages/public/QRCodeScannerPage.vue';
//import CameraPage from './pages/public/CameraPage.vue';
//import UploadPage from './pages/public/UploadPage.vue';
//import AllActivityPage from './pages/public/AllActivityPage.vue';
import DirectMessagesPage from './pages/public/DirectMessagesPage.vue';
</script>


<style>
#app {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 414px;
  height: 896px;
  background-color: #d0cccc;
}

.margin {
  margin-left: 10px;
}
</style>