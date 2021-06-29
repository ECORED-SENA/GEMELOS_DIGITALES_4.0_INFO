<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.svg')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0 Creación de Gemelos digitales de producto en Industria 4.0
          
          .h2 Información del programa
          .banner-principal__datos
            ul
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto creación de gemelos digitales de producto en industria 4.0 
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 22520109
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Total Horas: 
                p.banner-principal__datos__item__texto 48 Horas
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Duración en meses: 
                p.banner-principal__datos__item__texto 1
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto virtual

        .d-none.d-lg-block.col-lg-5
          .video
            | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/y4DPSvezf04" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p Bienvenidos al curso de #[strong creación de gemelos digitales de producto en industria 4.0], a través de la herramienta NX de siemens. Un gemelo digital, o digital twin, es una réplica virtual realizada a imagen y semejanza de un producto que permite su validación antes de la fabricación real.

    p.mt-3 Esta acción de formación pretende contribuir al fortalecimiento de los procesos formativos en modalidad virtual, de acuerdo con las necesidades actuales, en temas relacionados con la industria 4.0. Se encuentra enfocada en la elaboración de Gemelos Digitales de producto, a partir de la definición morfológica la pieza según las especificaciones de diseño y finaliza con la creación de la documentación.

    p.mt-3 El curso tiene una duración de 48 horas, la distribución de los contenidos se diseñó para un total de cuatro semanas. Cada una de las cuales estará comprendida por cuatro sesiones con una duración sugerida de 2 horas diarias.

    p.mt-3 #[strong Semana 1: introducción al sistema y roquizado en 2D;] teniendo en cuenta las especificaciones del producto, se elaboran los bocetos o croquis en 2D.

    p.mt-3 #[strong Semana 2: modelado de piezas;] basados en los croquis en 2D se crean los modelos digitales del producto en 3D, con el empleo de herramientas avanzadas para el modelado por operaciones en forma paramétrica facilitando la edición, ajuste y actualización de manera automática.

    p.mt-3 #[strong Semana 3: ensamble de piezas;] teniendo en cuenta los modelos se realizan los ensambles obteniendo como resultado el gemelo digital. Este módulo permite insertar cada una de las piezas y asignar relaciones geométricas de posición, verificar el movimiento y generar explosionado, lo que permite definir la configuración del gemelo digital.

    p.mt-3 #[strong Semana 4: generación de planos;] basados en la información que suministra el cliente se define la especificación del producto. Esto se logra mediante la creación de los planos de un conjunto de componentes o partes en forma automática; Una modificación en un modelo digital provoca la actualización de la información técnica del producto en el plano de dibujo.  
      

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5
    .titulo__template--a.mb-4
      span.h4 2. Justificación<br>del programa

    p La nueva realidad y demanda del sector productivo generada por la industria 4.0 que comprende: la transformación digital, la automatización de procesos, el internet de las cosas y el trabajo en la nube, exige cerrar la brecha del talento humano cualificado requerido por las empresas. El SENA comprometido con la misión de formar personal idóneo para que se integre exitosamente a su entorno laboral, ha implantado como estrategia de modernización, ambientes de formación dotados con herramientas de Diseño CAD especializadas en la creación de gemelos digitales que cuentan con las mismas características de un producto físico, herramientas CAE que permiten el análisis y validación de modelos virtuales de producto y aplicaciones CAM que permiten la Fabricación Asistida de los productos por Computador.

    p.mt-3 Esta acción de formación se encuentra enfocada en la elaboración de Gemelos Digitales de producto, se define morfológicamente la pieza según las especificaciones de diseño y se documenta el Gemelo Digital seleccionado según normativa.

    p.mt-3 Este tipo de formación es pertinente en todo el territorio nacional y se encuentran cursos en empresas privadas y algunas universidades especializadas en el tema. A nivel internacional se ubican cursos en diferentes países, se ofertan diplomados, post grados y cursos cortos.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5
    .titulo__template--a.mb-4
      span.h4 3. Competencias #[br] a desarrollar

    p 220101013 - Digitalizar dibujo de acuerdo con técnicas de modelación virtual y manuales técnicos.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5
    .titulo__template--a.mb-4
      span.h4 4. Perfil #[br] de ingreso

    ul.lista-ul
      li 
        i.fas.fa-check
        | Conocimientos básicos de dibujo y diseño en la industria.
      li 
        i.fas.fa-check
        | Los que defina el centro de formación.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5
    .titulo__template--a.mb-4
      span.h4 5. Estrategia #[br] metodológica

    p Centrada en la construcción de autonomía para garantizar la calidad de la formación en el marco de la formación por competencias, el aprendizaje por proyectos o el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportadas en la utilización de las tecnologías de la información y la comunicación, integradas, en ambientes abiertos y pluritecnológicos, que en todo caso recrean el contexto productivo y vinculan al instructor con la realidad cotidiana y el desarrollo de las competencias.

    p.mt-3 Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el que hacer y los resultados de aprendizaje que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:

    ul.lista-ul
      li 
        i.fas.fa-check
        | El instructor - Tutor
      li 
        i.fas.fa-check
        | El entorno
      li 
        i.fas.fa-check
        | Las TIC
      li 
        i.fas.fa-check
        | Trabajo colaborativo


  //- Créditos
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5
    .titulo__template--a.mb-4
      span.h4 Créditos

    Creditos

  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({}),
}
</script>
<style lang="sass">
.banner-principal__info .h1, .banner-principal__info p, .banner-principal__info .h2
    color: #12263f !important
</style>
