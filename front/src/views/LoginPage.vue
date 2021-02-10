<template>
    <div id="LoginPage">
        <div class="Login">
            <h1>User Login</h1>
            <input type="text" placeholder="Username" name="uname" required>
            <input type="password" placeholder="Password" name="psw" required>
            <button type="submit">Login</button>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
#loginPage {
    height: 90vh;
    display: flex;
}
.Login {
    width: 25%;
    height: 60%;
    margin: auto;
    align-self: center;
    background-color: #74C5FF;
    border: 5px solid #45AAF2;
    border-radius: 10px;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    h1 {
        color: white;
        font-size: 2em;
        text-align: center;
        font-family: 'Lobster', cursive;
    }
}
</style>