<template>
    <div>
        <p>{{name}}</p>
        <button @click="updateName">change name</button>
    </div>
</template>

<script>

export default {
    data(){
        return{
            name:'Belle',
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