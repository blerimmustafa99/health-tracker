<template>
    <div class="main-h-screen bg-gray-100 p-6">
        <h1 class="text-3xl font-bold mb-6 text-center">Health Tracker Dashboard</h1>
        <MetricsOverview />
        <WeeklyProgressChart />
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import MetricsOverview from '@/components/MetricsOverview.vue';
import WeeklyProgressChart from '@/components/WeeklyProgressChart.vue';

export default defineComponent({
    components: {
        MetricsOverview,
        WeeklyProgressChart
    }
})
</script>

<style scoped></style>
