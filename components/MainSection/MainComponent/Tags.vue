<template>
  <div  data-aos="fade-right"
        data-aos-delay="500"
        data-aos-once="true">
      <h2 class="pb-2 text-right">برچسب ها</h2>
      <hr class="pb-2">
      <ul class="text-right ">  
        <li v-for="tag in tags" :key="tag.id">
          <span>
            {{tag.title}}
          </span>
          <arrow-left-icon size="1x" class="custom-class"></arrow-left-icon>
        </li>
      </ul>
  </div>
</template>

<script>
import { ArrowLeftIcon } from 'vue-feather-icons'

export default {
  components: {
    ArrowLeftIcon
  },
  data(){
    return{
      tags:[
        {id:1,title:"ارز دیجیتال"},
        {id:2,title:"بیت کوین"},
        {id:3,title:"بلاکچین"}
      ]
    }
  }
}
</script>

<style scoped>
ul li{
    padding: .5rem;
    border-bottom: 1px solid rgba(0, 0, 0, 0.116);
    display: flex;
    justify-content: space-between;
    color: grey;
    align-items: center;
    cursor: pointer;
}
</style>