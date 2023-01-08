<script setup lang="ts">
import Card from '../Card.vue'

defineProps<{ }>()

</script>

<template>
    <div class="home-page-container">
        <input type="text" v-model="input" placeholder="Rechercher un joueur..." />
        <Card />
    </div>
</template>

<style scoped>
.home-page-container {
    margin: 2em 0;
    background-color: lightgray;
    padding: 2em;
    border-radius: 5%;
}

</style>
