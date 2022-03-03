<template>
  <div class="container">
    <Navbar />
  </div>
</template>

<script>
import Navbar from './components/Navbar'

export default {
  name: 'App',
  components: {
    Navbar,
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@500;700&display=swap');

* {
  box-sizing: border-box;
  margin: 0;
}

body {
  font-family: Poppins;
}

.container {
  color: #34313D;
}


</style>
