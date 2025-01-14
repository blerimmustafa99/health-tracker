<template>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
        <div class="bg-white p-4 shadow rounded animate-slideFromLeft">
            <h2 class="text-lg font-bold">Weight</h2>
            <p class="text-2xl font-semibold text-teal-500">70 kg</p>
        </div>
        <div class="bg-white p-4 shadow rounded animate-slideFromLeft">
            <h2 class="text-lg font-bold">Calories</h2>
            <p class="text-2xl font-semibold text-orange-500">1,500 kcal</p>
        </div>
        <div class="bg-white p-4 shadow rounded animate-slideFromRight">
            <h2 class="text-lg font-bold">Exercise</h2>
            <p class="text-2xl font-semibold text-blue-500">30 min</p>
        </div>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({})
</script>
