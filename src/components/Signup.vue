<template>
    <div class="register">
    <img class="logo" src="../assets/books.jpeg"/>
    <h1>Sign Up</h1>

    <input type="text" placeholder="Enter Name" />
    <input type="text" placeholder="Enter Email" />
    <input type="password" placeholder="Enter Password" />
    <button>Sign Up</button>
    </div>
</template>

<script>
export default {
    name : 'SignUp'
}
</script>

<style>
    .logo{
        width: 100px;
    }
    .register input{
        width: 250px;
        height: 40px;
        padding-left: 20px;
        display: block;
        margin-bottom: 23px;
        margin-right: auto;
        margin-left: auto;
        border: 1px solid skyblue;
        border-radius: 15px;
    }
    .register button{
        border: none;
        background-color: #0376b8;
        color: #fff!important;
        border-radius: 15px;
        height: 35px;
        width: 80px;
        margin-bottom: 25px;
    }
    .register{
        border: 2px solid;
        width: 600px;
        height: 550px;
        margin: auto;
    }
</style>