<script setup lang="ts">
import Login from '../components/Login.vue'
</script>

<template>
    <main>
        <div class="login">
            <Login />
        </div>
    </main>
</template>

<style>
    main{
        display: flex;
        justify-content: center;
        align-items: center;
        height: 60vh;
    }

    .login{
        width: 50%;
        height: 50%;
    }
</style>
