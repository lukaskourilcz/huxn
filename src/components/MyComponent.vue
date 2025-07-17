<script setup>

const tutorial = "https://www.youtube.com/watch?v=pgWZLS75Nmo"
const amazingImage = "https://res.cloudinary.com/ddxwdqwkr/image/upload/c_scale,w_700,f_auto/v1742105960/building-large-javascript-applications/case-studies/advanced/cover.webp"
const altText = "just a random pic"
const imageWidth = 400
const imageHeight = 400

</script>

<template>

<a :href="tutorial">Vue Tutorial</a>
<img :src="amazingImage" :alt="altText" :width="imageWidth" :height="imageHeight">

</template>