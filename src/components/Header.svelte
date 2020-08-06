<script>
  export let segment;
</script>

<style>
  img {
    height: 90px;
  }
  .text-transparent {
    color: transparent;
  }
</style>

<!-- <header> -->
<div class="row pt-2 px-2">
  <div class="col text-md-center">
    <a href="#">
      <img src="images/logo-bellabike.png" alt="" />
    </a>
  </div>
</div>
<nav class="navbar navbar-expand-lg navbar-light bg-light sticky-top ">
  <a class="navbar-brand" href="#" />
  <button
    class="navbar-toggler"
    type="button"
    data-toggle="collapse"
    data-target="#navbarSupportedContent"
    aria-controls="navbarSupportedContent"
    aria-expanded="false"
    aria-label="Toggle navigation">
    <span class="navbar-toggler-icon" />
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mx-auto">
      <li class="nav-item">
        <a
          rel="prefecth"
          class={segment === undefined ? 'nav-link active' : 'nav-link'}
          href="/">
          Home
          <span class="sr-only">(current)</span>
        </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Arriendos</a>
      </li>
      <li class="nav-item dropdown">
        <a
          class="nav-link dropdown-toggle"
          href="#"
          id="navbarDropdown"
          role="button"
          data-toggle="dropdown"
          aria-haspopup="true"
          aria-expanded="false">
          Tours
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
          <a class="dropdown-item" href="#">Santiago Histórico</a>
          <a class="dropdown-item" href="#">Santiago Moderno</a>
          <a class="dropdown-item" href="#">Cerro San Cristobal</a>
        </div>
      </li>
      <li class="nav-item">
        <a
          rel="prefecth"
          class={segment === 'nosotros' ? 'nav-link active' : 'nav-link'}
          href="nosotros">
          Nosotros
        </a>
      </li>

    </ul>
  </div>
</nav>
<!-- </header> -->
