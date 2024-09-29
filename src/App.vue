<script setup lang="ts">
import Navbar from './components/Navbar.vue'
import Card from './components/Card.vue'
</script>

<template>
  <main>
    <Navbar />
    <section style="background-color: #eee;">
        <div class="text-center container py-5">
            <h4 class="mt-4 mb-5"><strong>Produtos</strong></h4>
            <Card />
        </div>
    </section>
  </main>
</template>
