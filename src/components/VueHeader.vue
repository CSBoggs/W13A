<template>
    <header>
        <h1>Top Navigation Bar</h1>
        <h1>Login and stuff</h1>
    </header>
</template>

<script>
export default {
    name: "VueHeader"
}
</script>


<style scoped>
header {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    height: 10vh;
    line-height: 5vh;
}

h1{
color: rgb(0, 102, 255);
margin-left: 5vw;
margin-right: 5vw;

}
</style>