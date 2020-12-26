<template>
    <div id="app">
        <img src="./assets/logo.png">
        <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
        <communication></communication>
    </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import communication from './components/communication'

export default {
    name: 'app',
    components: {
        HelloWorld,
        communication
    }
}
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
}
</style>
