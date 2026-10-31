<script setup>
defineProps({
    pesan: String,
});
</script>

<template>
    <main class="flex min-h-screen flex-col items-center justify-center gap-3 bg-white text-neutral-900">
        <h1 class="text-4xl font-semibold tracking-tight">Raffaw Studio</h1>
        <p class="text-neutral-500">{{ pesan }}</p>
    </main>
</template>