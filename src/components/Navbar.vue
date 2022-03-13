<template>
  <nav
    class="navbar navbar-expand-lg navbar-light" id="bg-nav"
  >
    <div class="container">
          <router-link class="nav-link navbar-brand" to="/">web Latihan</router-link>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto">
          <li class="nav-item">
            
          <router-link class="nav-link" to="/">Home</router-link>
          </li>
          <li class="nav-item">
          <router-link class="nav-link" to="/about">About</router-link>
          </li>
        </ul>
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
          <router-link class="nav-link" id="bg-login" to="/login">Masuk</router-link>
          </li>
          <li class="nav-item" id="bg-regis">
          <router-link class="nav-link" id="bg-regis" to="/daftar">Daftar</router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style>
#bg-nav{
    background-image: radial-gradient(circle at 8.79% 53.61%, #00ffff 0, #39ffff 25%, #53bcf2 50%, #4e7ea0 75%, #3c4b5a 100%);
    height: auto;
    
}
#bg-login{
    color: #fff;
    background: #3c4b5a;
    width: auto;
    border-radius: 5px;
    margin: 5px;
    padding: 10px;
    text-align: center;
}
#bg-regis{
    margin: 5px;
    padding: 2px;
    background: #3c4b5a;
    width: auto;
    height: 45px;
    position: relative;
    box-shadow: #3c4b5a;
    border-radius: 5px;
}
#bg-regis a{
    
    color: #fff;
    text-align: center;
}

</style>