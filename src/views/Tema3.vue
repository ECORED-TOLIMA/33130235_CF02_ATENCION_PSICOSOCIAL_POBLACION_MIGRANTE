<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero(data-aos="fade-right")
        span 3
      h1 Marco normativo que orienta la estrategia integral
    
    .bloque-texto-g.bloque-texto-g--inverso.color-primario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema3/img01.jpg')})`}" data-aos="fade-left"
      )
      .bloque-texto-g__texto.p-4(data-aos="fade-right")
        p.mb-0 El marco normativo que respalda la Estrategia Integral de Acompañamiento Psicosocial Migratorio reúne políticas, leyes, decretos y guías técnicas que orientan la atención a la población migrante, retornada y de acogida en Colombia. Su propósito es garantizar la protección de los derechos humanos, la salud mental y el bienestar psicosocial mediante lineamientos claros y la articulación entre entidades estatales, organismos internacionales y comunidades.

    p.mb-5 Este marco incorpora los compromisos asumidos por el país en los ámbitos nacional e internacional, entre los que se destacan la Política Integral Migratoria (Ley 2136 de 2021), la Ley 1616 de 2013, que establece el marco de acción para la salud mental en Colombia, y las orientaciones del Ministerio de Salud y Protección Social, las cuales definen principios, enfoques y procedimientos para la intervención psicosocial en contextos de movilidad humana.

    .row.justify-content-center.align-items-end.mb-4
      .col-lg-3.col-6.mb-lg-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/tema3/img02.png' alt="Imagen decorativa")
      .col-lg-7(data-aos="fade-left")
        .cajon.color-secundario.p-4.mb-4  
          p.mb-0 Así mismo, protocolos, rutas y guías técnicas vigentes como el Programa de Atención Psicosocial y Salud Integral a Víctimas (PAPSIVI) y las orientaciones para la atención psicosocial a población migrante, fortalecen la gestión interinstitucional y garantizan respuestas integrales, éticas y sostenibles frente a los desafíos que plantea la movilidad humana.
        p.mb-0 El análisis de este marco regulatorio permite al aprendiz comprender la estructura jurídica e institucional que sustenta la estrategia, reconociendo cómo la normatividad se traduce en acciones concretas de acompañamiento, inclusión y promoción del bienestar psicosocial en los territorios.

    separador
    #t_3_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 3.1 Políticas nacionales e internacionales que sustentan la estrategia
    
    p.mb-5 La Estrategia Integral de Acompañamiento Psicosocial Migratorio se apoya en un conjunto de políticas, leyes y lineamientos internacionales que garantizan la protección de los derechos humanos, la atención en salud mental y la integración socioeconómica de las personas en situación de movilidad humana. Este marco orienta el diseño y la implementación de acciones territoriales, asegurando que las instituciones actúen de manera articulada y bajo principios de inclusión, corresponsabilidad y enfoque diferencial.

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8.order-lg-1.order-2(data-aos="fade-right")
        .cajon.color-primario.p-4.mb-4  
          p.mb-0 En el ámbito nacional, destacan la Ley 2136 de 2021, que establece la Política Integral Migratoria (PIM), y la Ley 1616 de 2013, que define el marco para la salud mental en el país, incluyendo la obligación de brindar atención psicosocial con enfoque comunitario. A esto se suma la normatividad sectorial del Ministerio de Salud y Protección Social, que orienta la atención a población migrante, retornada y de acogida mediante rutas, guías y protocolos especializados.
        p.mb-0 En el plano internacional, Colombia se adhiere a instrumentos como el Pacto Mundial para una Migración Segura, Ordenada y Regular (2018), que promueve la cooperación global y el respeto por los derechos de las personas migrantes. Estas directrices complementan los esfuerzos nacionales y fortalecen la capacidad institucional para ofrecer atención psicosocial basada en estándares internacionales.
      .col-lg-3.col-6.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/tema3/img03.png' alt="Imagen decorativa")

    p.mb-5 A continuación, se presenta una síntesis de las políticas y normas que sustentan la estrategia:

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h5 Tabla 2.
      i Políticas nacionales e internacionales que fundamentan la estrategia
    .tabla-a.color-acento-contenido.mb-5
      table(data-aos="zoom-in"  alt="Texto alternativo tabla")
        thead
          tr(data-aos="fade-right")
            th(style="background-color: #CFF5FF; width: 35%;") Norma o instrumento
            th(style="background-color: #CFF5FF; width: 10%;") Ámbito
            th(style="background-color: #CFF5FF; width: 10%;") Año
            th(style="background-color: #CFF5FF; width: 45%;") Aportes a la estrategia
        tbody
          tr(data-aos="fade-right")
            td(style="background-color: #F6F6F6;") Ley 2136 - Política Integral Migratoria (PIM).
            td(style="background-color: #F6F6F6;") Nacional
            td(style="background-color: #F6F6F6;") 2021
            td(style="background-color: #F6F6F6;") Establece principios de inclusión, corresponsabilidad y participación social. Fortalece la gobernanza migratoria y garantiza acceso a servicios psicosociales, salud, educación y empleo.
          tr(data-aos="fade-right")
            td Ley 1616 - Ley de Salud Mental.
            td Nacional
            td 2013
            td Reconoce la salud mental como un derecho fundamental. Obliga a brindar atención psicosocial integral con enfoque comunitario.
          tr(data-aos="fade-right")
            td(style="background-color: #F6F6F6;") Decreto 216 - Estatuto Temporal de Protección para Migrantes Venezolanos (ETPV).
            td(style="background-color: #F6F6F6;") Nacional
            td(style="background-color: #F6F6F6;") 2021
            td(style="background-color: #F6F6F6;") Facilita la regularización y acceso a servicios sociales y de salud, incluyendo atención psicosocial.
          tr(data-aos="fade-right")
            td PAPSIVI - Programa de Atención Psicosocial y Salud Integral a Víctimas.
            td Nacional
            td 2012
            td Provee lineamientos para la atención psicosocial basada en enfoque diferencial, comunitario y de derechos.
          tr(data-aos="fade-right")
            td(style="background-color: #F6F6F6;") Pacto Mundial para la Migración Segura, Ordenada y Regular.
            td(style="background-color: #F6F6F6;") Internacional
            td(style="background-color: #F6F6F6;") 2018
            td(style="background-color: #F6F6F6;") Promueve cooperación internacional, protección de derechos humanos y acceso a servicios psicosociales para población migrante.
          tr(data-aos="fade-right")
            td Principios Rectores de los Desplazamientos Internos (ONU).
            td Internacional
            td 1998
            td Establecen estándares para la protección y atención de personas desplazadas, incluyendo apoyo psicosocial.
    
    p En conjunto, estas políticas nacionales e internacionales conforman el soporte jurídico y técnico que orienta la Estrategia Integral de Acompañamiento Psicosocial Migratorio, asegurando que las acciones implementadas en los territorios respondan a estándares de protección, inclusión y bienestar. Al articular lineamientos nacionales con compromisos globales, el país fortalece su capacidad para garantizar intervenciones psicosociales coherentes, culturalmente pertinentes y centradas en la dignidad humana, consolidando así una respuesta integral frente a los desafíos derivados de la movilidad humana.

    separador
    #t_3_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 3.2 Lineamientos de atención psicosocial del Ministerio de Salud y Protección Social

    p.mb-5 Los lineamientos emitidos por el Ministerio de Salud y Protección Social constituyen la base técnica para orientar la atención psicosocial en el país, asegurando intervenciones integrales, basadas en evidencia y con enfoque diferencial. Este marco establece criterios para garantizar que las acciones respondan a las necesidades específicas de la población migrante, retornada y de acogida.

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema3/img04.jpg')})`}" data-aos="fade-right"
      )
      .bloque-texto-g__texto.p-4(data-aos="fade-left")
        p.mb-0 Los Lineamientos de Atención Psicosocial (Minsalud, 2021) plantean que la intervención psicosocial es un proceso continuo que articula la promoción de la salud mental, la prevención de riesgos emocionales y el fortalecimiento de redes familiares y comunitarias. Así mismo, incorporan enfoques transversales de derechos humanos, género, ciclo vital e interculturalidad, lo que asegura que la atención sea culturalmente pertinente y coherente con las dinámicas territoriales.

    .row.justify-content-center.mb-5
      .col-lg-11
        .tarjeta-avatar-b(data-aos="fade-right")
          .tarjeta-avatar-b__img(style="min-width: 10%; left: 0%")
            img(src='@/assets/curso/tema3/img05.svg' alt="Imagen decorativa")
          .tarjeta.BG01
            .p-4
              p.mb-0 El #[strong Decreto 0729 de 2025], que reglamenta la Política Nacional de Salud Mental, dispone que la atención psicosocial debe integrarse en los Planes Territoriales de Salud. Esto implica fortalecer las capacidades institucionales locales, garantizar equipos interdisciplinarios y asegurar la participación activa de las comunidades en la planificación y evaluación de las acciones.

    p Con el fin de orientar la intervención en contextos de movilidad humana, el Ministerio ha desarrollado lineamientos específicos para la atención a población migrante, incluyendo herramientas para la detección temprana, la intervención en crisis, la gestión comunitaria del riesgo y la articulación con la cooperación internacional.
    p.mb-5 A continuación, se presentan los elementos clave que estructuran los lineamientos del Ministerio de Salud y Protección Social:

    .BGIMG03.px-md-5.px-4.mb-5(data-aos="zoom-in")
      .row.justify-content-center
        .col-lg-4.col-sm-6.col-8.mb-lg-0.mb-4
          img(src='@/assets/curso/tema3/img06.png' alt="Imagen decorativa")
        .col-lg-8
          .py-4
            SlyderF.color-acento-botones(columnas="col-lg-6 col-xl-4" data-aos="zoom-in")
              .tarjeta.BG04.p-4
                .row.justify-content-center.mb-4
                  .col-lg-8.col-6
                    img(src='@/assets/curso/tema3/img07.svg' alt="Imagen decorativa")
                p.mb-0 Enfoques transversales: derechos humanos, género, interculturalidad y curso de vida.
              .tarjeta.BG04.p-4
                .row.justify-content-center.mb-4
                  .col-lg-8.col-6
                    img(src='@/assets/curso/tema3/img08.svg' alt="Imagen decorativa")
                p.mb-0 Promoción y prevención en salud mental como ejes centrales del acompañamiento.
              .tarjeta.BG04.p-4
                .row.justify-content-center.mb-4
                  .col-lg-8.col-6
                    img(src='@/assets/curso/tema3/img09.svg' alt="Imagen decorativa")
                p.mb-0 Detección temprana de afectaciones psicosociales y atención en crisis.
              .tarjeta.BG04.p-4
                .row.justify-content-center.mb-4
                  .col-lg-8.col-6
                    img(src='@/assets/curso/tema3/img10.svg' alt="Imagen decorativa")
                p.mb-0 Integración obligatoria de la atención psicosocial en los Planes Territoriales de Salud.
              .tarjeta.BG04.p-4
                .row.justify-content-center.mb-4
                  .col-lg-8.col-6
                    img(src='@/assets/curso/tema3/img11.svg' alt="Imagen decorativa")
                p.mb-0 Fortalecimiento de equipos interdisciplinarios y articulación intersectorial.
              .tarjeta.BG04.p-4
                .row.justify-content-center.mb-4
                  .col-lg-8.col-6
                    img(src='@/assets/curso/tema3/img12.svg' alt="Imagen decorativa")
                p.mb-0 Participación comunitaria en la planeación y evaluación de las acciones.
              .tarjeta.BG04.p-4
                .row.justify-content-center.mb-4
                  .col-lg-8.col-6
                    img(src='@/assets/curso/tema3/img13.svg' alt="Imagen decorativa")
                p.mb-0 Coordinación con organismos internacionales como OIM, ACNUR y OPS.

    p Este conjunto de orientaciones permite consolidar una atención psicosocial coherente, oportuna y sostenible, ajustada a las necesidades reales de las poblaciones en movilidad humana.

    separador
    #t_3_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 3.3 Protocolos, rutas y guías técnicas vigentes
    
    p.mb-5 Los protocolos, rutas y guías técnicas constituyen herramientas esenciales para garantizar una atención psicosocial organizada, homogénea y adaptada a las necesidades de la población migrante, retornada y de acogida. Estos instrumentos permiten que las acciones se desarrollen de manera articulada entre los sectores salud, protección, cooperación internacional y las entidades territoriales, asegurando que cada persona reciba una atención oportuna y culturalmente pertinente.

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-5.order-lg-1.order-2(data-aos="fade-right")
        .cajon.color-primario.p-4
          p.mb-0 En el ámbito nacional, uno de los referentes principales es la #[strong Ruta Integral de Atención Psicosocial y Salud Integral a Víctimas (PAPSIVI)], la cual ha servido como base para estructurar procesos de acompañamiento a personas afectadas por desplazamiento, migración forzada y emergencias humanitarias. Este modelo aporta orientaciones para el diagnóstico, la intervención y el seguimiento, fortaleciendo la reconstrucción emocional, la integración comunitaria y la articulación institucional.
      .col-lg-5.col-10.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/tema3/img14.png' alt="Imagen decorativa")

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-10
        p.mb-0 A su vez, la #[strong Guía Técnica de Atención Psicosocial a Población Migrante y Retornada] (Minsalud, 2022) ofrece lineamientos específicos para la identificación temprana de afectaciones emocionales, la gestión de casos, la remisión a servicios especializados y la coordinación con organizaciones como ACNUR, OIM y las secretarías de salud.

    .row.justify-content-center.mb-5
      .col-lg-3.col-6.mb-lg-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/tema3/img15.png' alt="Imagen decorativa")
      .col-lg-9(data-aos="fade-left")
        p Los lineamientos del Ministerio de Salud incluyen además la #[strong Ruta Integral de Atención en Salud (RIAS) para Salud Mental], que define pasos claros para la detección, atención inicial, intervención y seguimiento de personas con necesidades psicosociales asociadas a la movilidad humana. Esta ruta se articula con la oferta institucional del sistema de salud y con rutas sectoriales como la #[strong Ruta de Atención para Migrantes Venezolanos], que orienta procedimientos de regularización, afiliación al sistema, atención en servicios básicos y mecanismos de referencia.
        p.mb-0 Asimismo, documentos como el CONPES 4100 de 2022 señalan la importancia de que las entidades territoriales adopten protocolos ajustados a sus realidades locales, asegurando la articulación interinstitucional, la adaptación cultural y la sostenibilidad de las acciones en salud mental y apoyo psicosocial.
    
    p.mb-5 A continuación, se presenta una ruta simplificada que sirve como guía práctica para equipos psicosociales en territorio:

    .mb-4.d-flex(data-aos="fade-right")
      .d-flex.flex-wrap.align-items-center.pe-4.tarjeta.color-secundario(style="border-radius: 20px;")
        img(src='@/assets/curso/temas/img01.svg' style="max-width: 32px; margin-left: -16px;")
        h3.col.ps-3.mb-0 Ruta operativa para la implementación del acompañamiento psicosocial
    
    .row.justify-content-center.mb-5
      .col-lg-6.order-lg-1.order-2(data-aos="fade-right")
         AcordionA.color-acento-botones(tipo="b" clase-tarjeta="tarjeta BG03" data-aos="zoom-in")
          div(titulo="Diagnóstico y caracterización")
            p.mb-0 Incluye identificación de necesidades individuales, familiares y comunitarias, mapeo de factores de riesgo y protección, y análisis de condiciones socioculturales de la población migrante y de acogida.
          div(titulo="Planificación de la intervención")
            p.mb-0 Define objetivos, actividades, metodologías y responsables, articulando la oferta institucional y las necesidades detectadas en el diagnóstico.
          div(titulo="Ejecución participativa")
            p.mb-0 Despliega acciones individuales, familiares y comunitarias como orientación psicosocial, grupos de apoyo, actividades culturales y procesos de integración social, incorporando enfoques diferenciales.
          div(titulo="Seguimiento y evaluación")
            p.mb-0 Monitorea avances, identifica alertas, retroalimenta el proceso y ajusta las estrategias según la evolución de los casos y la respuesta comunitaria.
          div(titulo="Retroalimentación interinstitucional")
            p.mb-0 Fortalece la coordinación entre sectores, garantiza continuidad en los procesos y facilita la articulación con salud, protección y cooperación internacional.
      .col-lg-4.col-sm-6.col-8.order-lg-2.order-1.px-4.mb-lg-0.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/tema3/img16.png' alt="Imagen decorativa")

    p En conjunto, estos protocolos, rutas y guías técnicas conforman un marco integral que orienta a los equipos psicosociales en la identificación oportuna de riesgos, la intervención diferenciada y el seguimiento articulado de cada caso. Su aplicación permite responder de manera coordinada a las necesidades de las personas migrantes, garantizando procesos de acompañamiento que respetan su dignidad, reconocen sus trayectorias de vida y facilitan su acceso efectivo a servicios de salud, protección y bienestar. De este modo, se promueve una atención coherente con los estándares nacionales y con los principios de inclusión, interculturalidad y enfoque de derechos.

</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
