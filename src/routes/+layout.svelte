<header>
  <div style="margin-right:10px;">SVELTE</div>
  <div class="nav">
    <ul>
      <li><a href="/paginaAlan">Alan</a></li>
      <li><a href="/paginaFrancisco">Francisco</a></li>
      <li><a href="/paginaPaul">Paul</a></li>
      <li><a href="/paginaRamiro">Ramiro</a></li>
      <li><a href="/paginaMartin">Papi Martin XD</a></li>
      <li><a href="/paginaEdionel">Edionel</a></li>
      <li><a href="/paginaDaniel">Daniel</a></li>
    </ul>

  </div>
</header>

<slot></slot>

<style>
  *{
    margin:0;
    padding:0;
    box-sizing:border-box;
  }
  header{
    display:flex;
    justify-content:space-between;
    width:100%;
    background-color:#369;
    color:#fff;
    padding:10px;
  }
  .nav{
    text-align:right;
  }
  ul li{
    display:inline-block;
    margin-right:10px;
  }
  a{
    color:#fff;
    text-decoration:underline;
  }
</style>