<template>
 <div class="main">
  <nav class="nav container px-4 mx-auto">
   <router-link to="/" class="link">
    <img src="@/assets/logo.png" alt="" class="logo" />
    <h1 class="name">Parexellence</h1></router-link
   >
  </nav>
 </div>
</template>

<script>
 export default {}
</script>

<style>
 .main {
  position: relative;
  top: -10em;
 }
 .nav {
  display: flex;
  justify-content: center;
  align-items: center;
 }
 .link {
  display: flex;
 }
 .logo {
  height: 40px;
 }
 .name {
  font-size: 2rem;
  color: #ededee;
  padding-left: 10px;
 }
</style>
