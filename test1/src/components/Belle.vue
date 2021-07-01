<template>
    <div>
        <h1>{{title}}</h1>
        <p>{{name}}</p>
        <button @click="updateName">change name</button>
    </div>
</template>

<script>

export default {
    //props:['title'],
    props:{
        title:{
            type:String,
            required:false,
            default:'default Title'
        },
        name:{
            type:String,
            required:false,
            default:"default name"
        }
    },
    data(){
        return{
            //name:'Belle',
        }
    },

    methods:{
        updateName(){
            this.name = 'Belle Updated'
        }
    }
}
</script>

<style scoped>

</style>