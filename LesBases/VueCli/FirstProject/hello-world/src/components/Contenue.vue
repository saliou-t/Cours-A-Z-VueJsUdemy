<template>
    <div>
        <div v-html="text"></div>
    </div>
</template>
<script>

   export default{
       data() {
           return {
               text: '<h2>Voici le nouveau conteune de nouvel component !!! </h2>'
           }
       },
   }

</script>
<style>
</style>