<template>
    <div class="credits">
        <div class="grey">Created by</div>
        <div>Muhil Venkat</div>
        <div>Trinethr Neelagandan</div>
        <div class="grey">Class 9C</div>
    </div>
</template>

<style scoped>
.credits {
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    display: flex;
    gap: 0.25rem;
    width: 100%;
    height: 3rem;
    justify-content: center;
    align-items: center;
    background-color: #010A168f;
    backdrop-filter: blur(10px); 
}
.credits div::after {
    content: ' • ';
}.credits div:last-child::after {
    content: '';
}
</style>