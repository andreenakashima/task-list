<template>
    <div v-for="task in tasks">{{ task.text }}</div>
</template>

<script>
    export default {
        name: 'Tasks',
        props: {
            tasks: Array
        }
    }
</script>