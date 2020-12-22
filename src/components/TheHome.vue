<template>
     <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png" /> -->
   
    <banner/>
    <br><br>
    <tarjetas/>
    <br><br>
    <testimonios/>
    <br><br>
    <the-footer/>
   

  </div>

</template>


<script>
import axios from 'axios';
import banner from '../components/banner.vue';
import Tarjetas from '../components/Tarjetas.vue';
import Testimonios from '../components/testimonios.vue';
// @ is an alias to /src
import TheFooter from "../components/TheFooter.vue";

export default {
    name: "Home",
  components: {
    
    banner,
    Tarjetas,
    Testimonios,
    TheFooter,
    
  },
     data() {
        return {
            datos: null,
            
        };
    },
    mounted() {
     axios.get('articulo/list')
    .then(response => (this.datos = response.data));

    },
    
}
</script>