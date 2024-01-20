<script lang="ts">
  import CajaMagica from "./CajaMagica.svelte"
  //Aqui el Javascript
  var saludo = "Hola Latam y Europa!"
</script>


<h1>{saludo}</h1>


<h1>Bien como pueden ver</h1>
<h2>Los que estan conectados</h2>
<h3>Lo facil que es editar el CSS</h3>


<CajaMagica />



<style>
  /* AQUI EL CSS */
  ul li{
    font-weight:bold;
  }
  a{
    display:block;
    margin-bottom:1em;
  }
</style>