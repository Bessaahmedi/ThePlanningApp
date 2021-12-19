<template>
    <header>
        <img v-bind:src="picture" v-bind:alt="logo"/>
    </header>
</template>

<script>


export default {
    name: 'Header',

    data () {
        return {
            picture: "./assets/logo.png",
        }
    },
}

</script>

<style scoped>
/* Scoped Stylesheet - counts for the header tag ONLY in this component */

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 20px;
    padding: 30px;
    background-color: pink;
}

img {
    height: auto;
}
</style>