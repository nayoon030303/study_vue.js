<template>
  <div>
    <h1>This is Home Page</h1>
    <form action="">
      <!-- <InputFeild :name="name" @update-name="name=$event.target.value"></InputFeild> -->
      <InputFeild v-model="name"></InputFeild>
       <br>
      <button>Submit</button>
    </form>
    {{name}}
  </div>
</template>

<script>

 import InputFeild from '@/components/InputField.vue';

export default{
  components:{
    InputFeild
  },
  data(){
    return{
      name: ''
    }
  },
  methods:{
    updateName(name){
      this.name = name;
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
