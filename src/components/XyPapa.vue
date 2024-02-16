<script setup>
defineProps({
    xyTitle: {
        type: String,
        required: false
    }
})
</script>

<template>
    <div>
        <h2 class="green">{{ xyTitle }}</h2>
    </div>
</template>