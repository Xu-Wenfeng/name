<template>
    <div class="app">
        <h1>大帅比是谁？</h1>
        <Person/>
    </div>
</template>

<script>
    import Person from './components/Person.vue'
    export default  {
        name:'App',
        components:{Person}
    }
</script>

<style>
    .app{
        background-color:#ddd;
        box-shadow:0 0 10px;
        padding:10px;
    }
</style>