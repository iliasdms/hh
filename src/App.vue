<template>
  <div id="nav">
 <!--<div class="navbar navbar-dark bg-primary"> </div> -->
        <!--<a class="navbar-brand" href="#">MédiDomService</a>-->
      <!-- <ul class="nav">
            <li class="nav-item pr-4">
                <router-link class="nav-link text-white" to="/admin">Admin</router-link>
            </li>
            <li class="nav-item pr-4">
                <router-link class="nav-link text-white" to="/patient">patient</router-link>
            </li>
            <li class="nav-item pr-4">
                <router-link class="nav-link text-white" to="/users-area">medecin</router-link>
            </li>-->
          <!-- <li class="nav-item">
                <router-link class="nav-link text-white" to="/Login" id="log">Login</router-link>
            </li>-
        </ul>-->
 <!--</div>-->
    <div class="container py-4">
        <router-view />
    </div>
    </div>
</template>

<script>
export default {
  name: 'App',
  mounted() {
    this.$router.push('/login');
  },
}
</script>

<style >


body {
  font-family: "Open Sans", sans-serif;
  color: #444444;
  overflow-x: hidden;
}
.py-4{
  max-width: none;
  padding: 0;
}
</style>
