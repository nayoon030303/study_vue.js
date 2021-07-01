<template>
  <div class="about">
    <h1>This is an about page</h1>
    <BelleCoder/>
  </div>
</template>

<script>
import BelleCoder from '@/components/Belle.vue';

export default{
  data(){
    return{
      title:5
    }
  },
  components:{
    BelleCoder
  }
}

</script>
