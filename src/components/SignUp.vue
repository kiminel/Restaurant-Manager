<template>
    <h1 class="header">Sign Up</h1>

    <div class="sign-up">
        <input type="text" placeholder="Email" />
        <input type="text" placeholder="Password" />
        <button>Sign Up</button>
    </div>
</template>
  
<script>

export default {
    name: 'SignUp',
}
</script>
  
<style>
.header {
    color: #2b83d5;
}

.sign-up input {
    width: 80%;
    height: 35px;
    padding-left: 20px;
    display: block;
    margin: 20px auto;
    border: 1px solid #799cd2;
    border-radius: 25px;
}

.sign-up button {
    cursor: pointer;
    width: 20%;
    height: 30px;
    display: block;
    margin: 20px auto;
    border: #799cd2;
    border-radius: 25px;
    color: white;
    background-color: #2b83d5;
}
</style>