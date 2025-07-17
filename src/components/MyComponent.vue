<script setup>

const myMessage = 'Yellow World'
const myNumber = 100

function add(x, y){
    return x + y
}

</script>

<template>
    <h1>{{myMessage}}</h1>
    <h2>{{myNumber}}</h2>
    <h3>2+2 = {{2+2}}</h3>
    <h2>Add Two Numbers: {{ add(2, 2) }}</h2>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Beatae ea illo eveniet voluptas unde sapiente impedit minus doloribus, laboriosam blanditiis porro error? Saepe beatae reiciendis architecto, nostrum eos commodi sapiente.</p>
</template>