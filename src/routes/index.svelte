<style>
  .carousel-inner img {
    max-height: 100vh;
    object-fit: cover;
    filter: grayscale(60%);
  }
  #carousel .overlay {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    background-color: rgba(0, 0, 0, 0.5);
    color: white;
  }
  #carousel span {
    background-color: rgb(40, 41, 91, 0.6);
  }
</style>

<svelte:head>
  <title>BellaBike Tours and Bike Rental</title>
</svelte:head>

<div id="carousel" class="carousel slide" data-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img
        class="d-block w-100"
        src="images/fondo.jpg"
        alt="images/fondo.jpg" />
    </div>
  </div>
  <div class="overlay carousel-caption">
    <div class="overlay-container h-100">
      <div class="row align-items-center justify-content-center h-100 w-100">
        <div class="col-md-6">
          <h1>
            <span>Disfruta de Santiago en bici</span>
          </h1>
          <p class="d-none d-md-block text-white">
            <span>
              ¿De visita en la ciudad? Vives muy lejos como para llegar en
              bicicleta al centro. Entonces Bellabike es lo que necesitas. Los
              parques y ciclovías de la ciudad te esperan.
            </span>
          </p>
          <div class="row justify-content-arround">
            <div class="col py-1">
              <a href="tours" class="btn btn-bellabike">Conocer los tours</a>
            </div>
            <div class="col py-1">
              <a href="nosotros" class="btn btn-bellabike">Arrendar una bici</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
