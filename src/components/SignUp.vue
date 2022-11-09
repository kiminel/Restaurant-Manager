<template>
    <h1 class="header">Sign Up</h1>

    <div class="sign-up">
        <div class="field">
            <input type="text" placeholder="Email">
            <fa icon="envelope" />
        </div>
        <div class="field">
            <input type="text" placeholder="Password" />
            <fa icon="lock" />
        </div>
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
    color: #799cd2;
}

.field {
    width: 80%;
    height: 35px;
    padding-left: 20px;
    display: block;
    margin: 20px auto;
    border: 1px solid #799cd2;
    border-radius: 25px;
}

.sign-up input {
    width: 90%;
    height: 32px;
    border:none;
    border-radius: 25px;
}

.sign-up input:focus {
    outline: none;
    border: none;
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
    background-color: #799cd2;
}

.sign-up button:hover {
    color: white;
    background-color: #6ad0c8;
    box-shadow: 0 0 4px #6ad0c8;

}
</style>