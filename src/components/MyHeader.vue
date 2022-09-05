<template>

<nav class="navbar navbar-expand-lg bg-light">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Navbar</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">       
          <router-link class="nav-link active" aria-current="page" to="/">HOME</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/contact">CONTACT</router-link>
        </li>
        <li class="nav-item">
            <router-link class="nav-link" to="/aboutus">ABOUT US</router-link>
        </li>      
      </ul>
    </div>
  </div>
</nav>

</template>

<script>
    export default {
        name: 'MyHeader',
        data(){
            return{}
        }
    }
</script>
