<script>
  export let segment;
  // Abre el dropdown menu al hacer hover
</script>

<style>
  img {
    height: 100px;
  }
  .text-transparent {
    color: transparent;
  }
</style>

<!-- <header> -->
<div class="container-fluid">
  <div class="row pt-2 px-2 bg-dark">
    <div class="col text-md-center pb-3">
      <a href="#">
        <img src="images/logo-naranjo.png" alt="" />
      </a>
    </div>
  </div>
</div>
<nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top ">
  <a class="navbar-brand" href="#" />
  <button
    class="navbar-toggler "
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
        <div class="btn-group">
          <a
            rel="prefecth"
            href="tours"
            class={segment === 'tours' ? 'btn btn-link nav-link active' : 'btn btn-link nav-link'}>
            Tours
          </a>
          <a
            href="Tours"
            class="btn btn-link nav-link dropdown-toggle dropdown-toggle-split"
            data-toggle="dropdown"
            aria-haspopup="true"
            aria-expanded="false">
            <span class="sr-only">Tours</span>
          </a>
          <div class="dropdown-menu">
            <a class="dropdown-item" href="#">Santiago Histórico</a>
            <a class="dropdown-item" href="#">Santiago Moderno</a>
            <a class="dropdown-item" href="#">Cerro San Cristobal</a>
          </div>
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
