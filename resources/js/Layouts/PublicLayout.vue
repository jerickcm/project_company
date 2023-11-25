<script setup>
import { Link } from "@inertiajs/vue3";
import Footer from "../Components/Footer/Footer.vue";
</script>

<template>
    <div class="min-h-screen bg-gray-100">
        <div>
            <!-- <div id="holder"> -->
            <!-- <div id="body"> -->
            <main></main>
            <!-- <div style="min-height: 460px"></div> -->
            <!-- </div> -->
            <slot />
            <Footer />
            <!-- </div> -->
        </div>
    </div>
</template>

<style scoped></style>
