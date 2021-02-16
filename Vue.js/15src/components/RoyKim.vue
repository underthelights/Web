<template>
    <div>
        <p> {{ name }}</p>
        <button @click="updateName">His Real Name</button>
    </div>
    
</template>

<script>
export default {
    data(){
        return{
            name: 'Roy Kim',
        }
    },
    methods:{
        updateName(){
            this.name = 'Sung-Woo Kim'
        }
    }
}
</script>

<style scoped>

</style>