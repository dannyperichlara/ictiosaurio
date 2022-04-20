<template>
  <div>
    <b-navbar  type="dark" variant="info">
      <b-navbar-brand style="width: 100%; text-align: center;">
        <img src="/images/logo.png" style="max-width: 100%; height: 90px" />
      </b-navbar-brand>
    </b-navbar>
    <div class="container col-xxl-8 px-4 pt-0 pb-5">
      <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
        <div class="col-10 col-sm-8 col-lg-6">
          <img src="/images/01.jpeg" class="d-block mx-lg-auto img-fluid" alt="Bootstrap Themes" width="700" height="500" loading="lazy">
        </div>
        <div class="col-lg-6">
          <h1 class="display-3 fw-bold lh-1 mb-3">Libertad para dedicarte a tu negocio</h1>
          <p class="lead">Creamos contenido para tus redes sociales, para que tú puedas dedicar el 100% de tu tiempo a lo tuyo.</p>
          <div class="d-grid gap-2 d-md-flex justify-content-md-start">
            <button type="button" v-b-modal.hablemos class="btn btn-primary btn-lg px-4 me-md-2">Hablemos. ¡La conversación es gratis!</button>
          </div>
        </div>
      </div>
      <div class="small mb-1">Varios emprendedores ya han confiado en nosotros ⭐⭐⭐⭐⭐</div>
      <img src="/images/prisma.png" style="height: 40px; max-width: 32%" class="mr-4">
      <img src="/images/kippa.png" style="height: 40px; max-width: 32%" class="mr-4">
      <img src="/images/fluss.png" style="height: 40px; max-width: 32%" class="mr-4">
      <img src="/images/cromativa.png" style="height: 40px; max-width: 32%" class="mr-4">
    </div>

    <b-container fluid style="background-color: #EEE">
      <b-container>
        <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
          <div class="col-10 col-sm-8 col-lg-6">
            <img src="/images/youtube.jpeg" class="d-block mx-lg-auto img-fluid" alt="Bootstrap Themes" width="700" height="500" loading="lazy">
          </div>
          <div class="col-lg-6">
            <h2 class="display-4 fw-bold lh-1 mb-3">Somos creadores de contenido</h2>
            <p class="lead">Nos dedicamos a la creación de contenido para redes sociales y distintas plaformas online. Algunos ejemplos de lo que hacemos son:</p>
            <ul class="lead">
              <li>Publicaciones para Instagram y Facebook</li>
              <li>Reels para Tik-Tok e Instagram</li>
              <li>Videos para YouTube e infografías animadas</li>
              <li>Artículos de blog y videoblogs</li>
              <li>Podcasts</li>
            </ul>

            <p class="lead">También te ayudamos en procesos de adaptación digital:</p>
            <ul class="lead">
              <li>Creamos tu tienda online</li>
              <li>Capacitamos a tus colaboradores en el uso de nuevas tecnologías</li>
              <li>Creamos aplicaciones móviles para tu negocio</li>
            </ul>
            <div class="d-grid gap-2 d-md-flex justify-content-md-start">
                <button type="button" v-b-modal.hablemos class="btn btn-primary btn-lg px-4 me-md-2 mt-4">Ven a conocernos</button>
            </div>
          </div>
        </div>
      </b-container>
    </b-container>

    <div class="container col-xxl-8 px-4 py-5">
      <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
        <div class="col-10 col-sm-8 col-lg-6">
          <img src="/images/notes.jpeg" class="d-block mx-lg-auto img-fluid" alt="Bootstrap Themes" width="700" height="500" loading="lazy">
        </div>
        <div class="col-lg-6">
          <h2 class="display-4 fw-bold lh-1 mb-3">¿Cómo funciona?</h2>
          <p class="lead"><b>Paso 1</b>: Nos reunimos para conocerte y saber en qué etapa está tu negocio, cómo estás manejando tus redes sociales, qué plataformas usas y cuáles tus inquietudes y dificultades.</p>
          <p class="lead">
            <b>Paso 2</b>: Establecemos junto a ti un presupuesto periódico y un calendario de contenidos adecuados según el rubro de tu empresa y los distintos segmentos de clientes de tu negocio.
          </p>
          <p class="lead">
            <b>Paso 3</b>: Te entregamos periódicamente los contenidos creados y te ayudamos en la publicación. Incluso podemos ayudarte en la publicidad online.
          </p>
          <p class="lead">
            <b>Paso 4</b>: Medimos el rendimiento de las publicaciones y te entregamos un plan de optimizaciones para mejorar tus indicadores clave.
          </p>
          <div class="d-grid gap-2 d-md-flex justify-content-md-start">
              <button type="button" v-b-modal.hablemos class="btn btn-primary btn-lg px-4 me-md-2 mt-4">Reunámonos</button>
          </div>
        </div>
      </div>
    </div>

    <div class="container col-xxl-8 px-4 py-5">
      <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
        <div class="col-10 col-sm-8 col-lg-6">
          <img src="/images/02.jpeg" class="d-block mx-lg-auto img-fluid" alt="Bootstrap Themes" width="700" height="500" loading="lazy">
        </div>
        <div class="col-lg-6">
          <h2 class="display-4 fw-bold lh-1 mb-3">¿Por qué nosotros?</h2>
          
          <h3 class="">Porque también somos emprendedores</h3>
          <b-container><p>A diferencia de nuestros competidores, quienes formamos la agencia Ictiosaurio tenemos nuestros propios emprendimientos y llevamos años aplicando los conocimientos que ofrecemos.</p></b-container>

          <h3 class="">Porque te entregamos resultados</h3>
          <b-container><p>No basta con hacer publicaciones y listo. Es necesario medir la efectividad de las publicaciones para saber si vamos por el camino correcto. Nuestro trabajo no es a todo evento; lo importante es que a ti te vaya mejor.</p></b-container>

          <h3 class="">Porque trabajamos junto a ti</h3>
          <b-container><p>Tú mejor que nadie conoce tu empresa. Posiblemente ya llevas tiempo gestionando las redes sociales de tu empresa y, por lo tanto, sabes lo que funciona y no funciona. Nosotros no vamos a reinventar la rueda por ti; vamos a trabajar juntos para que dos cabezas piensen más que dos.</p></b-container>

          <h3 class="">Porque somos profesionales de verdad</h3>
          <b-container><p>A diferencia de nuestra competencia, nosotros no aprendimos en YouTube. Quienes somos parte de la Agencia Ictiosaurio somos profesionales de carrera en las áreas de Marketing y Redes Sociales, Ingeniería Comercial, Periodismo, Diseño Gráfico, Análisis de Datos y Producción Audiovisual. Pero además, todos tenemos una larga experiencia trabajando para nuestros propios emprendimientos, por lo que podemos decir con propiedad que nosotros sí sabemos lo que hacemos.</p></b-container>

          <div class="d-grid gap-2 d-md-flex justify-content-md-start">
              <button type="button" v-b-modal.hablemos class="btn btn-primary btn-lg px-4 me-md-2 mt-4">Ven a conocernos</button>
          </div>
        </div>
        
      </div>
    </div>

    <b-modal id="hablemos" title="BootstrapVue">
      <p class="my-4">Hello from modal!</p>
    </b-modal>
    
    <b-container fluid class="ictiosaurio p-5 text-white">
      <img src="/images/logo.png" style="max-width: 100%" />
      <p class="pl-4">Ictiosaurio, Agencia de Contenidos<br>(+56) 9 92948450<br>Punta Arenas. Chile</p>
    </b-container>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',

  head() {
    return {
      title: 'Ictiosaurio, Agencia de Contenidos. Creamos contenido para tus redes sociales, para que tú puedas dedicar el 100% de tu tiempo a lo tuyo.'
    }
  },

  date () {
    return {
      color: '#FFAA00'
    }
  }
}
</script>

<style scoped>

.bg-info, .ictiosaurio {
  background-color: #f76d10 !important;
}

.btn-primary {
  background-color: #f76d10 !important;
  border-color: rgb(255, 207, 131) !important;

}
</style>