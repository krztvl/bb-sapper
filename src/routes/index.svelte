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
            <span>Disfruta de Santiago en bicicleta</span>
          </h1>
          <p class="d-none d-md-block text-white">
            <span>
              ¿De visita en la ciudad? Vives muy lejos como para llegar en
              bicicleta al centro. Entonces Bellabike es lo que necesitas. Los
              parques y ciclovías de la ciudad te esperan.
            </span>
          </p>
          <div class="container">
            <a href="tours" class="btn btn-bellabike">Conocer los tours</a>
            <a href="nosotros" class="btn btn-bellabike">Arrendar una bici</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<p>
  Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nihil pariatur
  ratione impedit aut assumenda ut accusamus facilis architecto vel obcaecati
  fuga magnam, esse perferendis, tenetur repellat nemo voluptates magni totam
  saepe? Alias corporis fugiat culpa suscipit praesentium aut libero voluptates!
  Repellendus voluptas non nam eveniet perspiciatis earum quasi, tempora facere?
  Perferendis consequuntur expedita culpa unde a blanditiis consectetur aliquam
  maxime quidem consequatur voluptatem deserunt nostrum placeat quis vero odit
  dolor delectus et, facilis rerum iusto numquam cumque. Esse, perspiciatis? Non
  error, perferendis perspiciatis rerum ea sit tempora harum laboriosam! Nobis,
  nostrum? Aliquam velit eius accusantium saepe provident! Voluptate, dolores
  voluptas quo voluptates distinctio nesciunt quidem aliquid magni repudiandae
  beatae atque! Fugiat, dolorem quisquam natus soluta hic deserunt ab illum at
  excepturi aut itaque. A sed illum itaque sapiente! Expedita quaerat, vel
  deserunt tenetur reprehenderit dolore nihil maxime corrupti aliquid ratione
  tempore distinctio odit minima rerum quam at exercitationem reiciendis
  veritatis soluta ipsum earum rem nisi culpa? Quasi fuga, nobis iure aliquam
  nihil repellat minus, mollitia atque quibusdam quis ratione harum ea nostrum
  reprehenderit ullam perferendis libero commodi? Perspiciatis laborum quae,
  hic, velit quaerat facere blanditiis nostrum adipisci, officiis minima aliquam
  dignissimos. Excepturi molestias asperiores nulla officiis vel sed ducimus
  fuga repudiandae quibusdam, veritatis nemo deleniti consequuntur velit odio
  sunt labore mollitia saepe error sequi, beatae qui aliquam ea quas? Magnam,
  voluptate dolore. Deserunt neque qui, veritatis totam debitis quas, cupiditate
  quidem iusto libero facilis aliquid! Praesentium eum voluptates hic quia
  cumque rerum vel ipsam repellat dicta aspernatur vero distinctio, eveniet
  perspiciatis fugiat maxime alias totam tenetur inventore ut laboriosam sequi!
  Rerum nemo cumque consectetur soluta distinctio illum dolores sunt minima
  nisi, officia saepe alias mollitia et, eveniet quis nesciunt minus ratione
  eaque corporis est. Facere tempore quas earum reprehenderit labore aperiam
  officiis magni fugit, itaque obcaecati debitis aut mollitia minima.
</p>
