<template>
  <div class="container">
    <div class="left">
      <h2>Shortly</h2>
      <h5>Features</h5>
      <h5>Pricing</h5>
      <h5>Resources</h5>
    </div>

    <div class="right">
      <button>Login</button>
      <button>Sign Up</button>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Navbar'
}
</script>

<style>

.container {
  padding: 10px 40px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 10px;
  width: 100%;
}

.left {
  display: flex;
  align-items: center;
  gap: 20px;
}

h2 {
  font-size: 24px;
}

h5, button {
  font-size: 15px;
  font-weight: bold;
  color: #9E9AA8;
}

button {
  border: none;
  border-radius: 28px;
  padding: 10px 20px;
  margin-left: 15px;
  background: none;
}

button:last-of-type {
  background-color: #2BD0D0;
  color: #FFFFFF;
}

</style>