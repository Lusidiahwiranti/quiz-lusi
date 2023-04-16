<template>
  <nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">PROFILE | Lusi Diah Wiranti</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarNavDropdown">
        <div class="mx-auto"></div>

        <ul class="nav-link">
          <li><a href="" class="active"><router-link to="/" style="color: #06060b;">Home</router-link></a></li>
          <li><a href="" class="active"><router-link to="/about" style="color: #06060b;">About</router-link></a></li>
          <li><a href="" class="active"><router-link to="/album" style="color: #06060b;">Album</router-link></a></li>

        </ul>
      </div>
    </div>
  </nav>


  <router-view />
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
  }
}
</script>

<style>
.navbar-expand-lg {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  text-align: center;
  background-color: rgba(171, 102, 102, 0.93);
  color: white;
  margin-top: 60px;
  display: flex;
  justify-content: space-between;
  padding: 5px 30px ;

}
.nav-link{
  display: flex;
  align-items: center;

}
.nav-link li{
  border: 1px solid #fff0f0;
  border-radius: 20px;
  list-style: none;
  margin-left: 20px;
  align-items: center;
  text-decoration: none;
  float: left;
}
.nav-link li a{
  text-decoration: none;
  color: white;
  font-weight: 500;
}
.active{
  text-align: center;
  padding: 10px;
}
.nav-link li a:hover {
  color: #06060b;
  font-size: 20px;
  transition: .2s;
  background-color: rgb(255, 240, 240);
}
</style>

