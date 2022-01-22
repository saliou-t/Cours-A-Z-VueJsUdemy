<template>
    <div class="list">
        <ul>
            <li v-for="(fruit, index) in fruits" v-bind:key="index" >{{ index }} : {{ fruit}} </li>
        </ul>
    </div>
</template>
<script>

export default {
    name: 'Liste',
    data(){
        return{
            fruits: ['Banane', 'Orange', 'Papaye','Goyave']
        }
    }
}
</script>
<style scoped src="./list.css" >
ul{
    background-color: red;
}
</style>