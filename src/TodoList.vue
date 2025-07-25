<script setup>
import { ref } from 'vue';

const newTask = ref('')
const tasks = ref([])

const addTask = () => {
    if(newTask.value.trim() !== ''){
        tasks.value.push(newTask.value)
        newTask.value = ''
    }
}

</script>

<template>
    <h1>todo list</h1>
</template>