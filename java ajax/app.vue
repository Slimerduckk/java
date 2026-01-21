<script setup>
    import { ref } from 'vue';

    let message = ref('Hello Vue!');
</script>

<template>
    <div class = "container">
        <h1>{{message}}</h>
        <button class ="button is-primary" v-on:click="message = 'Hello TA-24A!'"> Click me!</button>
        <input class = "input" v-bind:value ="message" v-on:input="input">
    </div>
</template>

<style>

</style>