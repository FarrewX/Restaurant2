<script setup>
import { useRoute } from 'vue-router';
import tonk from './tonk.vue'
import measai from './measai.vue';
import papa from './papa.vue'
import saiyut from './saiyut.vue'
import nimman from './nimman.vue'

const route = useRoute()
const id = parseInt(route.params.id)


</script>

<template>
    <body>
        <div v-if="id==0">
            <tonk />
        </div>
    </body>

    <body>
        <div v-if="id==1">
            <measai />
    </div>
    </body>

    <body>
        <div v-if="id==2">
            <papa />
    </div>
    </body>

    <body>
        <div v-if="id==3">
            <saiyut />
    </div>
    </body>

    <body>
        <div v-if="id==4">
            <nimman />
    </div>
    </body>

</template>

<style scoped>
body{
    text-align: center;
}
</style>