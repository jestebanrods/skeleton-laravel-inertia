<template>
    <div>
       Welcome {{ name }}
    </div>
</template>

<script setup>

defineProps({
    name: String,
});
</script>
