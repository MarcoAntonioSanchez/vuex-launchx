<template>

  <div class="home">

  <Header/>
  <Contador/>
  <Cuadrado/>
  <Botones/>
  <Footer/>
  
  </div>

</template>

<script>

import Contador from "../components/Contador.vue";
import Cuadrado from "../components/Cuadrado.vue";
import Botones from "../components/Botones.vue";
import Header from "../components/Header.vue";
import Footer from "../components/Footer.vue";


export default {
  name: 'HomeView',
  components: {
    Contador,
    Cuadrado,
    Botones,
    Header,
    Footer,
  }
}

</script>

<style>

.counter {
  font-size: 80px;
}

div {
  margin: 50px 0;
}

.buttons button {
  border: none;
  width: 5%;
  font-size: 40px;
  margin: 0 10px;
  background: #34495e;
  color: #ffffff;
  border-radius: 5px;
  transition: .3s ease-in-out;
}

button:hover {
  transform: scale(1.1);
  background: #41b883;
  cursor: pointer;
}

.cuadrado {
  font-size: 25px;
}

</style>