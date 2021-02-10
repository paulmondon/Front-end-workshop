<template>
    <div class="HeaderBar">
        <h1>PostApp</h1>
        <a href="#signup">Signup</a>
        <router-link to="/Login">Login</router-link>
        <a class="active" href="./">Home</a>
    </div>

</template>

<script>
    export default {

    }
</script>

<style lang="scss" scoped>
    .HeaderBar {
    background-color: #45AAF2;
    overflow: hidden;
    height: 100px;
}

.HeaderBar a {
    float: right;
    color: #f2f2f2;
    text-align: center;
    font-family: 'Roboto', sans-serif;
    padding: 14px 16px;
    text-decoration: none;
    font-size: 17px;
    padding: 40px 50px;
}

.HeaderBar h1 {
    float: left;
    font-family: 'Lobster', cursive;
    color: #f2f2f2;
    padding: 1px 50px;
    font-size: 40px;
}
</style>