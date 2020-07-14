<template>
  <div>      
      <HeaderMain/>
      <Main/>
      <!-- <NewPost/> -->
      <LastPosts/>
      
  </div>
</template>

<script>
// import Crypto from '@/assets/img/crypto.jpg';
import HeaderMain from './HeaderMain';
import MainMain from './MainMain';
import NewPost from './MainComponent/NewPost';
import LastPosts from './MainComponent/LastPosts';
export default {
    components:{
        HeaderMain,
        Main:MainMain,
        NewPost,
        LastPosts
    }
}
</script>

