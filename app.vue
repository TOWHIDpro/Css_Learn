<template>
  <div class="flex">
    <div class="nav-optione">
    <img src="assets/css/logo.svg" class="img" alt="">
      <a href="">home</a>
      <a href="">home</a>
      <a href="">home</a>
      <a href="">home</a>
    </div>
    <div class="log-sign">
      <button>Login</button>
      <button>Signup</button>
    </div>
  </div>
</template>

<style>
.flex{
  border: 2px solid black;
  display: flex;
  padding: 10px;
  justify-content: space-between;
  align-items: center;
}
.img{
  width: 30px;
  padding: 0px 10px;
}
.log-sign {
  width: 20%;
  display: flex-end;
  
}
.log-sign button{
  padding: 0px 10px;
  margin: 0px 10px;
}

.nav-optione {
  display: flex;
  width: 50%;
}

.nav-optione a {
  padding: 10px;
}
</style>
