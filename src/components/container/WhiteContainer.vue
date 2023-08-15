<template>
    <div class="WhiteContainer">
        <slot></slot>
    </div>
</template>

<script setup>
</script>

<style scoped>
.WhiteContainer {
    width: 414px;
    height: 896px;
    display: flex;
    align-items: center;
    flex-direction: column;
    background-color: white;
}
</style>