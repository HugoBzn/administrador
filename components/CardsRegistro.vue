<template>
  <div class="row">
    <div class="col-sm-4">
      <div class="card">
        <div class="card-body">
          <h5 class="card-title">Consumidores</h5>
          <center>
            <img
              src="@/assets/images/consumidores.jpg"
              width="250"
              alt=""
              srcset=""
            />
          </center>
          <p class="card-text">
            Los consumidores son personas las cuales buscan comprar o recibir
            productos a cambio de dinero.
          </p>
          <NuxtLink to="/register/consumidores" class="btn btn-primary">¡Registrar consumidores!</NuxtLink>
        </div>
      </div>
    </div>

    <div class="col-sm-4">
      <div class="card">
        <div class="card-body">
          <h5 class="card-title">Prestadores de servicios</h5>
          <center>
            <img src="@/assets/images/prestadores.png" width="250" alt="" />
          </center>
          <p class="card-text">
            Proveé servicios y/o productos para los usuarios consumidores.
          </p>
          <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
      </div>
    </div>

    <div class="col-sm-4">
      <div class="card">
        <div class="card-body">
          <h5 class="card-title">Entidades financieras</h5>
          <center>
            <img src="@/assets/images/financieras.jpg" width="250" alt="" />
          </center>
          <p class="card-text">
            Son las principales fuentes de ingresos, las cuales son un punto
            fuerte para esta asociación.
          </p>
          <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
      </div>
    </div>
  </div>
</template>
