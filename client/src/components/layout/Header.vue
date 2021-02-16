<template>
 <div class="header">

     <link href="https://fonts.googleapis.com/css?family=Open+Sans:300,400,600,700,800" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Roboto:100,300,400,500,700,900" rel="stylesheet">
    
    <link rel="apple-touch-icon" href="apple-touch-icon.png">

    <link rel="stylesheet" href="assets/css/bootstrap.min.css">
    <link rel="stylesheet" href="assets/css/bootstrap-theme.min.css">
    <link rel="stylesheet" href="assets/css/fontAwesome.css">
    <link rel="stylesheet" href="assets/css/hero-slider.css">
    <link rel="stylesheet" href="assets/css/owl-carousel.css">
    <link rel="stylesheet" href="assets/css/templatemo-style.css">
    <link rel="stylesheet" href="assets/css/lightbox.css">

    <script src="assets/js/vendor/modernizr-2.8.3-respond-1.4.2.min.js"></script> 
  <h1>Eth web Blog</h1>
   <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/contactas">Contact</router-link>
  </div>
</div>   
</template>

<script>
export default {
    name:"Header"
}
</script>

<style scoped>
.header {
  padding: 2px;
  text-align: center;
  background: #030505;
  color: white;
  font-size: 10px;
}
</style>