<template>
    <header>
        <h1>Task Tracker</h1>
    </header>
</template>

<script>
export default {
    name: 'Header',
}
</script>

<style scoped>
/* Scoped Stylesheet - counts for the header tag ONLY in this component */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 20px;
}
</style>