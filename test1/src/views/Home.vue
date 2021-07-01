<template>
  <div>
    <h1>This is Home Page</h1>
    <BelleCoder title="Home입니다." name="Belle Coder"/>

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
