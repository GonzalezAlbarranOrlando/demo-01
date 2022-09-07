<template>
  <nav class="navbar navbar-expand-lg bg-my-primary header-text">
      <div class="container-fluid container">
          <!--Logo-->
          <router-link class="nav-link active" aria-current="page" to="/">
              <img src="@/assets/logo.png" alt="" width="50" height=""/>
          </router-link>
          <!--Navbar toggler-->
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <!--Navbar-->
          <div class="collapse navbar-collapse" id="navbarNav">
              <ul class="navbar-nav">
                  <li class="nav-item">       
                      <router-link class="nav-link active" aria-current="page" to="/">
                          <i class="fa fa-home" style="font-size:20px; color:black"></i>
                          HOME
                      </router-link>
                  </li>
                  <li class="nav-item">
                      <router-link class="nav-link" to="/contact">
                          <i class="fa fa-phone" style="font-size:20px; color:black"></i>
                          CONTACT
                      </router-link>
                  </li>
                  <li class="nav-item">
                      <router-link class="nav-link" to="/aboutus">
                          <i class="fa fa-child" style="font-size:20px; color:black"></i>
                          ABOUT US
                      </router-link>
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
      return{
      }
    }
  }
</script>
