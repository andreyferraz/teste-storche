<template>

<div>
   <nav class="fixed-header">
 <!-- header-flex-box start -->
			<div class="header-flex-box">
			    <!-- logo start -->
				<a href="index.html" class="logo pointer-large animsition-link">
					<div class="logo-img-box">
				        <img class="logo-white" src="assets/images/logo/LOGOTIPO-06.png" alt="logo">
				        <img class="logo-black" src="assets/images/logo/LOGOTIPO-03.png" alt="logo">
			        </div>
		        </a><!-- logo end -->
      </div>
   </nav>
</div>




  <!-- <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/sobre">Sobre</router-link> |
    <router-link to="/servicos">O que fazemos?</router-link>
  </div> -->
  <router-view/>
</template>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
} */
</style>
