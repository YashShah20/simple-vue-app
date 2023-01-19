<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <hr>
    <div class="form">
      <input type="text" placeholder="Name">
      <input type="text" placeholder="Email">
      <input type="text" placeholder="Password">
      <input type="text" placeholder="Confirm Password">
      <button>Register</button>
    </div>
  </div>
  
</template>


<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
