<template>
    <div class="container-login">
      <div class="card-login">
        <div class="logo-login">
          <img class="logo" src="https://i.ibb.co/yVGxFPR/2.png" alt="">
          <h3>Registration</h3>
        </div>
        <form action="">
            <div class="input-box">
              <input type="text" id="username" placeholder="Username" name="Username">
              <input type="text" id="Email" placeholder="Email" name="Email">
              <input type="password" id="password" placeholder="Password" name="password">
              <input type="password" id="c-password" placeholder="Confirm Password" name="c-password">
              <input type="number" id="Phone" placeholder="Phone" name="Phone">
              <input type="submit" name="" value="Create Account">
            </div>
        </form>
        <div class="text-box">
          <span>Sudah Punya Akun? </span>
          <router-link to="/login">Login</router-link>
        </div>
      </div>
    </div>

    
    
</template>

<script>
export default {
  name: "Daftar",
};
</script>

<style>

h3{
  text-align: center;
  font-size: 28px;
  display: block;
  margin-bottom: 5px;
}
.card-login{
  max-height: 600px;
  max-width: 350px;
  background-color: rgb(196, 196, 196);
  padding: 40px 30px 30px 30px;
  margin: 80px auto;
  border-radius: 20px;
  box-shadow: 5px 5px 10px rgb(196, 196, 196);
}
.logo{
  width: 100px;
  display: block;
  margin-left: 33%;
  border-radius: 50%;
  margin-bottom: 10px;
}
.card-login input{
  width: 100%;
  margin-bottom: 20px;
}
.card-login input[type="text"], .card-login input[type="password"], .card-login input[type="number"]{
  border: none;
  border-bottom: 1px solid #262626;
  height: 35px;
  color: #000;
  background: transparent;
  font-size: 14px;
  padding-left: 10px;
}
.card-login input[type="text"]:hover, .card-login input[type="password"]:hover{
  color: rgb(196, 196, 196);
  border: 2px solid rgb(196, 196, 196);
  box-shadow: 0 0 5px rgb(196, 196, 196), 0 0 10px rgb(196, 196, 196), 0 0 10px rgb(196, 196, 196), 0 2px 0 black;
}
.card-login input[type="submit"] {
    border: none;
    outline: none;
    height: 40px;
    font-size: 16px;
    background: black;
    color: #fff;
    border-radius: 20px;
    cursor: pointer
}
.text-box{
  text-align: center;
  font-size: 14px;
}
.text-box a{
  text-decoration: none;
}
</style>
