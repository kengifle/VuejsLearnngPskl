<template>
    <div id="app">
        <Home msg="Hello worms!" />
        <inputEtLabel message ="yo mec" message_label="ceci est le label" typeInput="text"/>
        <inputEtLabel message ="yo meuf" message_label="ceci est le lapoolbel" typeInput="textarea"/>
    </div>
</template>

<script>
    import Home from './components/Home.vue';
    import inputEtLabel from './components/inputEtLabel.vue';
    export default {
        name: 'app',
        components: {
            Home,
            inputEtLabel
        }
    };
</script>

<style>
</style>
