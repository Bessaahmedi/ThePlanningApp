<template>
    <div class="same kalender">
        <a href="Kalender.vue"><h1>Kalender</h1></a>
    </div>
    <div class="same todo">
        <h1>To Do</h1>
    </div>
    <div class="same habit">
        <h1>Habit Tracker</h1>
    </div>
</template>


<script>


export default {
    name: 'Frontpage',
}
</script>

<style scoped>
/* Scoped Stylesheet - counts for the header tag ONLY in this component */
.same {
    width: 130px;
    height: 130px;
    background-color: #f2c2b7;
    
    font-size: 8px;
    justify-content: center;
    align-items: center;
    margin: 5em auto;
    padding: 55px 0;
    text-align: center;
    border-radius: 15px;
}
</style>