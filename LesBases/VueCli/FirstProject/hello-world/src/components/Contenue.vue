<template>
    <div>
        <div v-html="text"></div>
        <liste></liste>
    </div>
</template>
<script>
    import Liste from "./Liste/Liste.vue"

    export default{
        name: 'Contenue',
        data() {
            return {
                text: '<h2>Voici le nouveau conteune de nouvel component !!! </h2>'
            }
        },
        components: {
            'liste' : Liste
        }
    }
</script>
<style>
</style>