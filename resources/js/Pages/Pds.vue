<script setup>
import AppLayout from '@/Layouts/AppLayout.vue';
import Welcome from '@/Components/Welcome.vue';
</script>

<template>
    <AppLayout title="PDS">
        <template #header>
            <h2 class="font-semibold text-xl text-gray-800 leading-tight">
                Personal Data Sheet
            </h2>
        </template>

        <div>
        <h1 class="text-3xl font-semibold mb-4">Admin Dashboard</h1>
        <div class="bg-white rounded shadow p-4">
            <h2 class="text-xl font-semibold mb-2">Recent Activities</h2>
            <p class="text-gray-600">Lorem ipsum dolor sit amet...</p>
        </div>
    </div>
    </AppLayout>
</template>
