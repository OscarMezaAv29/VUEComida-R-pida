<template>
    <grid>
        <img v-bind:src="url" :alt="nombre">
        <h2>{{ nombre }}</h2>
        <p>{{ descripcion }}</p>
        <p>{{ precio }}</p>
    </grid>
</template>

<script>
import Grid from "./Grid.vue";
    export default {
    props: {
        url: {
            String,
        },
        nombre: {
            String,
        },

        descripcion: {
            String,
        },

        precio: {
            String,
        },
    },
    components: { Grid },
};
</script>

<style scoped>
    
    img {
        width: 14rem;
        height: 10rem;
        padding: 0.5rem;
        background-color: snow;
    }

    a {
        text-decoration: none;
        color: snow;
        background-color: #301675;
        padding: 0.3rem;
        border-radius: 5px;
        border: 1px solid #f2f2f2;

    }

    
</style>