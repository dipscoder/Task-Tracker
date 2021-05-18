<template>
    <header>
        <h1>{{title}}</h1>
        <Button text="Add Task" color="#4bb543" />
    </header>
</template>

<script>
import Button from './Button.vue';

export default {
    name: "Header",
    components: {
        Button
    },
    props: {
        title: {
            type: String,
            default: "Hello Ji"
        }
    }
}
</script>

<style>
    header{
       display: flex;
       justify-content: space-between;
       align-items: center; 
    }
</style>