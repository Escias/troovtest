<template>
  <section>
    <div class="headfoot">
      <h1 class="title">TroovTest</h1>
      <div>
        <button>Login</button>
        <button>SignIn</button>
      </div>
    </div>
    <div class="headfoot" id="foot">
      <h1 class="title">Developed by : Jimmy Lai</h1>
    </div>
  </section>
</template>

<script>
export default {
  name: "Home"
}
</script>

<style scoped>
html, body {
  margin: 0 !important;
  padding: 0 !important;
}
.headfoot{
  display: flex;
  justify-content: space-around;
  flex-direction: row;
  align-items: center;
  background-color: black;
}
.title{
  color: white;
  font-weight: bold;
}
#foot{
  position: fixed;
  bottom: 0;
  left: 0;
  right: 0;
}
</style>
