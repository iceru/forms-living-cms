<script setup>
import BreezeApplicationLogo from "@/Components/ApplicationLogo.vue";
import { Link } from "@inertiajs/inertia-vue3";
import Navigation from "@/Components/Navigation.vue";
</script>

<template>
    <div class="wrapper-body">
        <Navigation />
        <slot />
    </div>
</template>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Poppins:wght@400;500;600&family=Questrial&display=swap");

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.wrapper-body {
    font-family: "Poppins", sans-serif;
    color: $grey;
    overflow-x: hidden;
}
</style>
