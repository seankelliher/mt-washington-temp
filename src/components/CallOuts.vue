<script setup>
import { store } from "../composables/store.js";
</script>

<template>
    <section>
        <hgroup class="heading">
            <h2 class="bevan-regular">Seasonal temperatures</h2>
            <p class="roboto-serif four">Average temperatures, based on the years 2005 - 2023</p>
        </hgroup>
        <hgroup class="callout">
            <h3 class="roboto-serif six">Spring</h3>
            <p class="roboto-serif four">{{ store.springAvg }}&deg; F</p>
        </hgroup>
        <hgroup class="callout">
            <h3 class="roboto-serif six">Summer</h3>
            <p class="roboto-serif four">{{ store.summerAvg }}&deg; F</p>
        </hgroup>
        <hgroup class="callout">
            <h3 class="roboto-serif six">Autumn</h3>
            <p class="roboto-serif four">{{ store.fallAvg }}&deg; F</p>
        </hgroup>
        <hgroup class="callout">
            <h3 class="roboto-serif six">Winter</h3>
            <p class="roboto-serif four">{{ store.winterAvg }}&deg; F</p>
        </hgroup>
    </section>
</template>

<style scoped>
</style>