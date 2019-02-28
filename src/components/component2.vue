<template>
    <div class="component2">
        <label for="textfield">Label4textefield/label>
        <input id="textfield" type="text" v-bind:value="message"/>
    </div>
</template>

<script>
    export default {
        name: 'component2',
        props: {
            message: String
        }
    };
</script>

<style scoped>
    .component2 {
        color:red;
    }
</style>