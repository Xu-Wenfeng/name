<template>
    <div class="person">
        <button @click="change">大帅比是谁？</button>
    </div>
</template>

<script setup>
    import {ref} from 'vue'
    let name = ref('唐少！！')
    function change(){
        alert(name.value)
    }
    
</script> 

<style>
    .person{
        background-color:skyblue;
        box-shadow:0 0 10px;
        padding:20px;
    }
    button{
        margin:0 5px
    }
</style>