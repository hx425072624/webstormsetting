<template>
    <div id="app">
        <!--<img src="./assets/logo.png">-->
        <audio  id="sound" autoplay="autoplay" controls="1" loop="1">
            <source src="./assets/002.mp3" type="audio/mp3">
        </audio>
        <router-view/>
    </div>
</template>

<script>
/* eslint-disable no-new */
export default {
  name: 'App'
}
</script>

<style>
    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        margin-top: 60px;
    }
</style>
