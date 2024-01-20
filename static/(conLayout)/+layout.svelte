<script>
let mostrar = false  
</script>

{#if mostrar}
<h1>AQUI VA EL MENU</h1>
<a href="/"> Principal</a>
{/if}

<slot />