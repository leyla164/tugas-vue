<template>
   <Navbar style="background-color: ghostwhite;"></Navbar>
   <Header></Header>
   <Secim></Secim>
   <Carousel></Carousel>
   <Secimm2></Secimm2>
   <Gallery></Gallery>
   <Footer></Footer>  
</template>
<script setup> 
   import Navbar from './components/Navbar.vue';
   import Header from './components/Header.vue';
   import Secim from './components/Secim.vue';
   import Carousel from './components/Carousel.vue';
   import Secimm2 from './components/Secimm2.vue';
   import Gallery from './components/Gallery.vue';
   import { Footer } from 'flowbite-vue';
</script>