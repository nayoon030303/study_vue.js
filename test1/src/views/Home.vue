<template>
  <div>
    <h1>This is Home Page</h1>
    <BelleCoder/>

  </div>
</template>

<script>
import BelleCoder from '@/components/Belle.vue';

export default{
  components:{
    BelleCoder
  },

  data(){
    return{
      name: 'Belle'
    }
  }
}

</script>

<!-- scoped:이 파일만 -->
<style scoped>
h1{
  color: skyblue;
}
</style>
