<template>
  <div id="nav">
    <router-link to="/"><span>Home</span></router-link> 
    <router-link to="/about"><span>About</span></router-link>
    <router-link to="/shop"><span>Shop</span></router-link>
    <router-link to="/contact"><span>Contact Us</span></router-link>
    <a class="button"  href="#"><span>Sign Up</span></a>

  </div>
  <router-view/>
</template>

<style>
*
{
    margin: 0;
    padding: 0;
    box-sizing:border-box;
    font-family: sans-serif;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  background-color: #fff;
  
  padding: 15px;
}
 #nav span{
  padding: 15px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
  
}
.button{
  border: 1px solid #666;
  border-radius:20px;
  padding: 3px;
  background: #42b983;
}
</style>
