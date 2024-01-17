<script>
    import viteHelloWorld from './components/viteHelloWorld.vue';

    export default {
        data() {
            return {
                count: 0
            }
        },
        components: {
            viteHelloWorld
        }
    }
</script>

<template>
    <div>
        <h1><viteHelloWorld/></h1>
    </div>
</template>

<style scoped>
</style>
