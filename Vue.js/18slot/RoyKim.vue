<template>
    <div>
        <!-- <h1>{{ title }}</h1>
         -->
        <p>header</p>
        <slot name="header" :roy="roy"></slot>
        <p>header</p>
        <slot name="header"></slot>
        <p>footer</p>
        <!-- <p> {{ name }}</p><br>
        <button @click="updateName">His Real Name</button> -->
    </div>
    
</template>

<script>
export default {
    // props:['title'],
    props:{
        title:{
            type: String,
            default: 'default title'
        },
        name:{
            type: String,
            default: 'default name'
        }
    },
    data(){
        return{
            //name: 'Roy Kim',
            roy : 'singer'
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
