<template>
  <div class="form">
    <Header />
    <SignUp />
  </div>
</template>

<script>
import SignUp from './components/SignUp.vue';
import Header from './components/Header.vue';


export default {
  name: 'App',
  components: {
    SignUp,
    Header,
  }
}
</script>

<style>
#app {
  font-family: Arial, Helvetica, sans-serif;
  text-align: center;
  color: #3b3b3d;
  margin-top: 60px;
}

.form {
  border-radius: 25px;
  box-shadow: #799cd2 0px 7px 29px 0px;
  width: 45%;
  text-align: center;
  display: inline-block;
  align-items: center;
  margin: 5%;
}
</style>