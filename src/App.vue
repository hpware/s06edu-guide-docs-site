<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
    <nav>
        <ul>
            <a href="/"
                ><li><i class="bi bi-house"></i>首頁</li></a
            >
            <a href="/github/"
                ><li><i class="bi bi-github"></i>Github</li></a
            >
            <a href="/docs/"><li>Docs</li></a>
        </ul>
    </nav>
    <RouterView />
    <footer>
        <p>&copy; {{ new Date().getFullYear() }} 吳元皓</p>
    </footer>
</template>

<style scoped></style>
