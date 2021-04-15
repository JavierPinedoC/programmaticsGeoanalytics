<template>
  <div id="app" class="container is-fluid">
    <!--<nav class="navbar" role="navigation" aria-label="main navigation">
        <div class="navbar-brand">
          <a class="navbar-item" href="https://bulma.io">
            <img src="https://bulma.io/images/bulma-logo.png" width="112" height="28">
          </a>
      
          <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
          </a>
        </div>
      
        <div id="navbarBasicExample" class="navbar-menu">
          <div class="navbar-start">
            <a class="navbar-item">
              GEO-ANALYTICS
            </a>
      
            <a class="navbar-item">
              PROGRAMATICS
            </a>

            <a class="navbar-item">
                REGÍSTRATE
            </a>
      
          </div>
      
          <div class="navbar-end">
            <div class="navbar-item">
              <div class="buttons">
                <a class="button">
                    <i class="fas fa-shopping-cart"></i>
                </a>
                <a class="button">
                    <i class="fas fa-user-circle"></i>
                </a>
                <a class="button">
                    <i class="fas fa-globe"></i>
                </a>
              </div>
            </div>
          </div>
        </div>
      </nav>-->

    <nav class="navbar py-5 px-3 is-fixed-top">
      <div class="navbar-brand">
        <a class="navbar-item" href="#">
          <img src="../assets/nav-logo.png" alt="site-logo" />
        </a>
      </div>

      <div class="navbar-menu">
        <div class="navbar-end">
          <a href="#" class="navbar-item">GEO-ANALYTICS</a>
          <a href="#" class="navbar-item">PROGRAMMATICS</a>
          <a href="#" class="navbar-item">REGÍSTRATE</a>
          <a class="navbar-item">
            <i class="fas fa-shopping-cart"></i>
          </a>
          <a class="navbar-item">
            <i class="fas fa-user-circle"></i>
          </a>
          <a class="navbar-item">
            <i class="fas fa-globe"></i>
          </a>
        </div>
      </div>
    </nav>
    <!-- End Nav var -->

    <!-- Start body -->
    <section class="container is-fluid hero is-medium is-link block">
      <div class="hero-body has-text-centered">
        <p class="title">GEOANALYTICS</p>
        <p class="subtitle">Comprende a tus clientes a través del Big Data</p>
        <p class="subtitle">
          Con Geoanalytics, ten al alcance la información que tu campaña
          necesitaba
        </p>
      </div>
    </section>

    <section class="container is-fluid block" style="margin-top: 100px">
      <div class="columns">
        <div class="column">
          <div class="box">
            <article class="media">
              <div class="media-left">
                <figure class="image is-128x128">
                  <img
                    src="https://image.flaticon.com/icons/png/128/129/129639.png"
                    class=""
                    alt="Image"
                  />
                </figure>
              </div>
              <div class="media-content">
                <div class="content">
                  <p class="title has-text-left">
                    Nuestra tecnología te permitirá medir comportamientos de tu
                    audiencia por zona geográfica y hábitos de circulación
                  </p>
                </div>
              </div>
            </article>
          </div>
        </div>
        <div class="column">
          <div class="box">
            <article class="media">
              <div class="media-content">
                <div class="content">
                  <p class="title has-text-right">
                    Contamos con un amplio inventario exlusivo in-apps para
                    impactar a los segmentos que tu quieras
                  </p>
                </div>
              </div>
              <div class="media-right">
                <figure class="image is-128x128">
                  <img
                    src="https://image.flaticon.com/icons/png/128/633/633869.png"
                    class=""
                    alt="Image"
                  />
                </figure>
              </div>
            </article>
          </div>
        </div>
      </div>
    </section>
    <section class="container is-fluid block" style="margin-top: 100px">
      <p class="title has-text-centered">OBJETIVOS</p>

      <div class="columns">
        <div class="column">
          <figure class="image is-128x128 container">
            <img
              src="https://image.flaticon.com/icons/png/128/1439/1439841.png"
              class=""
              alt="Image"
            />
          </figure>
          <p class="subtitle is-size-6 has-text-centered">
            Conocer el comportamiento de movilidad de los clientes
          </p>
        </div>
        <div class="column">
          <figure class="image is-128x128 container">
            <img
              src="https://image.flaticon.com/icons/png/128/2654/2654432.png"
              class=""
              alt="Image"
            />
          </figure>
          <p class="subtitle is-size-6 has-text-centered">
            Lograr mayor éxito de la campaña
          </p>
        </div>
        <div class="column">
          <figure class="image is-128x128 container">
            <img
              src="https://image.flaticon.com/icons/png/128/1006/1006587.png"
              class=""
              alt="Image"
            />
          </figure>
          <p class="subtitle is-size-6 has-text-centered">
            Analizar el comportamiento de los clientes de la competencia
          </p>
        </div>
        <div class="column">
          <figure class="image is-128x128 container">
            <img
              src="https://image.flaticon.com/icons/png/128/2693/2693507.png"
              class=""
              alt="Image"
            />
          </figure>
          <p class="subtitle is-size-6 has-text-centered">
            Entender la temporalidad y condiciones del consumo
          </p>
        </div>
        <div class="column">
          <figure class="image is-128x128 container">
            <img
              src="https://image.flaticon.com/icons/png/128/1356/1356012.png"
              class=""
              alt="Image"
            />
          </figure>
          <p class="subtitle is-size-6 has-text-centered">
            Combinar comunicación externa y digital
          </p>
        </div>
      </div>
    </section>
    <section class="container is-fluid block" style="margin-top: 100px">
      <p class="title has-text-centered">SOLUCIONES / CAMPAÑAS</p>

      <div class="columns">
        <div class="column">
          <p class="subtitle has-text-centered">
            Descubre con tu campaña los perfiles de clientes que frecuentan:
          </p>
          <b-carousel
            v-model="words1.carousel"
            :indicator="words1.indicator"
            :animated="words1.animated"
            :has-drag="words1.drag"
            :autoplay="words1.autoPlay"
            :pause-hover="words1.pauseHover"
            :pause-info="words1.pauseInfo"
            :pause-info-type="words1.pauseType"
            :interval="words1.interval"
            :repeat="words1.repeat"
            :arrow="words1.arrow"
          >
            <b-carousel-item v-for="(carousel, i) in words1.carousels" :key="i">
              <div :class="` is-medium is-bold`">
                <div class="has-text-centered">
                  <h1 class="title">{{ carousel.title }}</h1>
                </div>
              </div>
            </b-carousel-item>
          </b-carousel>
          <p class="subtitle has-text-centered">
            Vea fácilmente su información desglozada por:
          </p>
          <b-carousel
            v-model="words2.carousel"
            :indicator="words2.indicator"
            :animated="words2.animated"
            :has-drag="words2.drag"
            :autoplay="words2.autoPlay"
            :pause-hover="words2.pauseHover"
            :pause-info="words2.pauseInfo"
            :pause-info-type="words2.pauseType"
            :interval="words2.interval"
            :repeat="words2.repeat"
            :arrow="words2.arrow"
          >
            <b-carousel-item v-for="(carousel, i) in words2.carousels" :key="i">
              <div :class="` is-medium is-bold`">
                <div class="has-text-centered">
                  <h1 class="title">{{ carousel.title }}</h1>
                </div>
              </div>
            </b-carousel-item>
          </b-carousel>
        </div>
        <div class="column">
          <p class="title has-text-centered">SEGMENTACIÓN DE AUDIENCIA</p>
          <p class="subtitle has-text-centered">
            Conozca los AD IDs de su audencia
          </p>
          <div class="has-text-centered">
            <b-button type="is-warning"
              >Inicia tu CAMPAÑA MOBILE + OOH</b-button
            >
          </div>
          <div class="columns">
            <div class="column">
              <figure class="image is-128x128 container">
                <img
                  src="https://image.flaticon.com/icons/png/128/4199/4199640.png"
                  class=""
                  alt="Image"
                />
              </figure>
            </div>
            <div class="column">
              <figure class="image is-128x128 container">
                <img
                  src="https://image.flaticon.com/icons/png/128/1503/1503614.png"
                  class=""
                  alt="Image"
                />
              </figure>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="container is-fluid block" style="margin-top: 100px">
      <div class="columns">
        <div class="column">
          <p class="title has-text-centered">
            ANALISIS DE VISITA A TIENDA FÍSICA
          </p>
          <p class="subtitle has-text-centered">
            Desarrolle con nostros una campaña de seguimiento a la audiencia de
            tu marca
          </p>

          <div class="columns">
            <div class="column">
              <p class="subtitle">
                Seleccionamos y categorizamos los AD ID meta de nuestra base de
                datos
              </p>

              <p class="subtitle">
                Damos seguimiento a esa audiencia y registramos la concurrencia
                con la marca
              </p>

              <p class="subtitle">
                Obtenga resultados sobre el comportamiento de su audiencia y
                determine la efectividad/eficiencia
              </p>
            </div>
            <div class="column">
              <figure class="image is-128x128">
                <img
                  src="https://image.flaticon.com/icons/png/128/3028/3028531.png"
                  class=""
                  alt="Image"
                />
              </figure>
              <figure class="image is-128x128 container">
                <img
                  src="https://image.flaticon.com/icons/png/128/2898/2898372.png"
                  class=""
                  alt="Image"
                />
              </figure>
              <div class="has-text-centered">
                <b-button type="is-warning" class=""
                  >Inicia tu ANÁLISIS TIENDA FÍSICA</b-button
                >
              </div>

              <p class="has-text-centered">*Necesario campaña ADID previa</p>
            </div>
          </div>
        </div>
        <div class="vl"></div>
        <div class="column">
          <p class="title has-text-centered">CAMPAÑA MOBILE + OOH</p>
          <p class="subtitle has-text-centered">
            Logre conjuntar medios digitales y físicos para su campaña
            publicitaria
          </p>

          <div class="columns">
            <div class="column">
              <figure class="image is-128x128 container">
                <img
                  src="https://image.flaticon.com/icons/png/128/2385/2385113.png"
                  class=""
                  alt="Image"
                />
              </figure>

              <div class="columns">
                <div class="column"></div>
                <div class="column">
                  <figure class="image is-128x128">
                    <img
                      src="https://image.flaticon.com/icons/png/128/3501/3501906.png"
                      class=""
                      alt="Image"
                    />
                  </figure>
                </div>
              </div>
              <div class="has-text-centered">
                <b-button type="is-warning" class=""
                  >Inicia tu ANÁLISIS TIENDA FÍSICA</b-button
                >
              </div>

              <p class="has-text-centered">*Necesario campaña ADID previa</p>
            </div>
            <div class="column">
              <p class="subtitle has-text-right">
                Concentra la información de los usuarios que interactuan con tu
                campaña publicitaria en un determinado tiempo
              </p>

              <p class="subtitle has-text-right">
                Procesamos esa información para designar el tipo de AD ID y la
                campaña correspondiente
              </p>

              <p class="subtitle has-text-right">
                El cliente tiene una doble exposición al anuncio.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="container is-fluid block" style="margin-top: 100px">
      <div class="columns">
        <div class="column">
          <p class="title has-text-centered">RE - TARGETING POR DISPLAY ADS</p>
          <p class="subtitle has-text-centered">
            Re-orienta estratégicamente los anuncios que visualiza y con los que
            interactua tu audiencia según datos de comportamiento en línea
          </p>
          <div class="has-text-centered">
            <b-button type="is-warning" class=""
              >Inicia tu CAMPAÑA RE-TARGET</b-button
            >
          </div>

          <p class="has-text-centered">*Necesario campaña ADID previa</p>
        </div>
        <div class="column">
          <div class="columns">
            <div class="column">
              <figure class="image is-128x128 container">
                <img
                  src="https://image.flaticon.com/icons/png/128/1466/1466966.png"
                  class=""
                  alt="Image"
                />
              </figure>
            </div>
            <div class="column">
              <figure class="image is-128x128 container">
                <img
                  src="https://image.flaticon.com/icons/png/128/1980/1980573.png"
                  class=""
                  alt="Image"
                />
              </figure>
            </div>
          </div>
        </div>
      </div>
    </section>

    <footer></footer>
  </div>
</template>

<script>
export default {
  data() {
    return {
      words1: {
        carousel: 0,
        animated: "slide",
        drag: false,
        autoPlay: true,
        pauseHover: false,
        pauseInfo: false,
        repeat: true,
        pauseType: "is-primary",
        interval: 3000,
        indicator: false,
        arrow: false,
        carousels: [
          { title: "Comercios" },
          { title: "Supermercados" },
          { title: "Estaciones de servicio" },
          { title: "Restaurantes" },
          { title: "Tiendas" },
        ],
      },
      words2: {
        carousel: 0,
        animated: "slide",
        drag: false,
        autoPlay: true,
        pauseHover: false,
        pauseInfo: false,
        repeat: true,
        pauseType: "is-primary",
        interval: 3000,
        indicator: false,
        arrow: false,
        carousels: [
          { title: "Horarios" },
          { title: "Frecuencia" },
          { title: "Distancia de viaje" },
          { title: "Modo de movilidad" },
          { title: "Fidelidad del cliente" },
        ],
      },
    };
  },
  methods: {},
};
</script>

<style scoped>
/* .right{
    float: right;
} */
.is-horizontal-right {
  justify-content: right;
}
.vl {
  border-left: 6px solid rgb(78, 78, 78);
  height: 500px;
  position: absolute;
  left: 50%;
  margin-left: -3px;
  top: 0;
}
</style>
