<template>
    <div id="app">
        <input v-model="message" type="text">
        <h2 class="message">{{ message }}</h2>
    </div>
</template>

<script>
    export default {
        data () {
            return{
                message: 'Hello World!',
            };
        },
    };
</script>

<style>
    .message {
        font-size: 18px;
        font-family: 'Roboto', sans-serif;
    }
</style>