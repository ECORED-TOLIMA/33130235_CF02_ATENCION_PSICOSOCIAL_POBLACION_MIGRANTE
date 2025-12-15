<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="fade-right")
      .titulo-principal__numero
        span 2
      h1 Implementación del acompañamiento psicosocial en contextos de movilidad humana
    
    figure.mb-5(data-aos="zoom-in")
      img(src='@/assets/curso/tema2/img01.png' alt="Imagen decorativa")
    
    .row.justify-content-center.mb-5
      .col-lg-10(data-aos="fade-right")
        .cajon.color-primario.p-4
          p.mb-0 La implementación del acompañamiento psicosocial en contextos de movilidad humana se concibe como un proceso estructurado orientado a responder de manera integral a las necesidades emocionales, sociales y comunitarias de las personas migrantes, retornadas y de las comunidades de acogida. Este proceso se fundamenta en fases planificadas, metodologías participativas y la articulación entre instituciones, sectores y territorios, con el propósito de garantizar intervenciones coherentes, sostenibles y con enfoque diferencial.
    
    p Desde esta perspectiva, la acción psicosocial se entiende como un medio para fortalecer la adaptación, la integración y la resiliencia, reconociendo las particularidades socioculturales de cada población y contexto territorial. La coordinación interinstitucional y la cooperación internacional permiten que los programas psicosociales se implementen bajo principios de eficiencia, equidad y respeto por la dignidad humana, contribuyendo a la reconstrucción del tejido social y a la garantía de derechos fundamentales.

    separador
    #t_2_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.1 Etapas y fases de la intervención psicosocial
    
    p.mb-5 La implementación de la estrategia psicosocial se desarrolla a través de etapas secuenciales y complementarias que garantizan una intervención integral y sostenida. Estas fases, que incluyen el diagnóstico, la intervención y el seguimiento, permiten comprender las condiciones individuales y colectivas de la población, orientar acciones estratégicas y valorar la efectividad del proceso.

    .row.justify-content-center.mb-4
      .col-lg-10.mb-5
        .titulo-sexto.color-acento-contenido(data-aos="fade-right")
          h5 Figura 2.
          i Etapas de la intervención psicosocial
        figure(data-aos="zoom-in")
          img.d-lg-flex.d-none(src='@/assets/curso/tema2/img02.svg' alt="La figura 2 representa el proceso de intervención psicosocial dividido en diagnóstico, intervención y seguimiento, como fases secuenciales y complementarias.")
          img.d-lg-none.d-flex(src='@/assets/curso/tema2/img03.svg' alt="La figura 2 representa el proceso de intervención psicosocial dividido en diagnóstico, intervención y seguimiento, como fases secuenciales y complementarias.")

      .col-lg-10.mb-5
        PasosA.color-acento-contenido.mb-5(tipo="l")
          div(data-aos="fade-left")
            p.mb-0 La primera etapa, correspondiente al diagnóstico, se centra en la identificación de factores de riesgo y protección, así como en la caracterización de los contextos familiares, sociales y comunitarios. Este análisis inicial permite reconocer las particularidades de la población migrante, retornada y de acogida, y establece las bases para una intervención pertinente.
          div(data-aos="fade-right")
            p.mb-0 En la etapa de intervención se implementan actividades orientadas al fortalecimiento emocional, la restauración de vínculos familiares y la cohesión social. Para ello, se aplican metodologías participativas y culturalmente pertinentes que favorecen la expresión de experiencias, el manejo emocional y la reconstrucción de redes de apoyo.
          div(data-aos="fade-left")
            p.mb-0 Finalmente, la fase de seguimiento busca asegurar la sostenibilidad de las acciones mediante el monitoreo continuo, la evaluación de avances y la retroalimentación entre actores institucionales y comunitarios. Este proceso permite ajustar las estrategias, garantizar la continuidad del acompañamiento y promover la autonomía de las comunidades.

      .col-lg-10
        .cajon.color-primario.p-4
          p.mb-0 De acuerdo con la OIM (2019), la planificación por fases incrementa la efectividad del acompañamiento psicosocial y fortalece la capacidad de resiliencia de las comunidades afectadas por procesos migratorios. Asimismo, el Ministerio de Salud y Protección Social (2018), mediante el modelo PAPSIVI (Programa de Atención Psicosocial y Salud Integral a Víctimas), destaca la importancia de articular la atención psicosocial con estrategias de salud pública, reconociendo las particularidades culturales y emocionales de cada grupo poblacional.

    separador
    #t_2_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.2 Herramientas y metodologías de aplicación
    
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/img04.jpg')})`}" data-aos="fade-right"
      )
      .bloque-texto-g__texto.p-4(data-aos="fade-left")
        p.mb-0 El acompañamiento psicosocial se desarrolla mediante herramientas y metodologías orientadas a trabajar los niveles individual, familiar y comunitario. Estas intervenciones favorecen la expresión emocional, la reconstrucción del tejido social, la adaptación cultural y la participación en el entorno. Según la Organización Panamericana de la Salud (OPS, 2019), la atención psicosocial debe fundamentarse en metodologías participativas y culturalmente pertinentes, capaces de fortalecer la autonomía, la resiliencia y el sentido de pertenencia.
    
    p.mb-5 A su vez, el Ministerio de Salud y Protección Social (2022) destaca la importancia de adaptar los instrumentos de intervención a las características socioculturales del territorio, fortaleciendo la acción intersectorial, la continuidad del acompañamiento y la identificación de recursos comunitarios. Estos enfoques posibilitan la creación de redes locales de apoyo, la generación de confianza y la consolidación de espacios de encuentro que articulan la experiencia individual con la acción colectiva.

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h5 Tabla 1.
      i Principales herramientas de intervención psicosocial
    .tabla-a.color-acento-contenido.mb-5
      table(data-aos="zoom-in"  alt="Texto alternativo tabla")
        thead
          tr(data-aos="fade-right")
            th(style="background-color: #CFF5FF; width: 35%;") Herramienta
            th(style="background-color: #CFF5FF; width: 20%;") Nivel de intervención
            th(style="background-color: #CFF5FF; width: 45%;") Propósito principal
        tbody
          tr(data-aos="fade-right")
            td(style="background-color: #F6F6F6;") Círculos de palabra.
            td(style="background-color: #F6F6F6;") Comunitario.
            td(style="background-color: #F6F6F6;") Promover la escucha activa, el diálogo y la construcción colectiva de significados.
          tr(data-aos="fade-right")
            td Talleres de expresión emocional (arte, escritura y diálogo).
            td Individual y grupal.
            td Facilitar la identificación y manifestación de emociones.
          tr(data-aos="fade-right")
            td(style="background-color: #F6F6F6;") Grupos de apoyo.
            td(style="background-color: #F6F6F6;") Comunitario.
            td(style="background-color: #F6F6F6;") Compartir experiencias, estrategias de afrontamiento y fortalecimiento mutuo.
          tr(data-aos="fade-right")
            td Orientación familiar.
            td Familiar.
            td Potenciar vínculos, roles y dinámicas de convivencia.
          tr(data-aos="fade-right")
            td(style="background-color: #F6F6F6;") Actividades artísticas, lúdicas y culturales.
            td(style="background-color: #F6F6F6;") Comunitario.
            td(style="background-color: #F6F6F6;") Impulsar la participación, la cohesión social y la integración comunitaria.

    p En conjunto, estas herramientas y metodologías consolidan procesos de acompañamiento psicosocial que responden de manera integral a las necesidades de las personas migrantes, retornadas y comunidades de acogida. Su aplicación articulada permite fortalecer la resiliencia, promover la participación comunitaria y generar condiciones favorables para la integración y el bienestar. Al basarse en enfoques participativos y culturalmente pertinentes, estas estrategias garantizan intervenciones más humanas, inclusivas y sostenibles en los distintos territorios.

    separador
    #t_2_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.3 Coordinación y articulación interinstitucional
    
    p.mb-5 La efectividad del acompañamiento psicosocial depende de una coordinación interinstitucional sólida y de una articulación territorial que garantice intervenciones coherentes, oportunas y complementarias. Esta acción transversal tiene como propósito consolidar estrategias y mecanismos de trabajo conjunto entre instituciones, sectores y niveles de gobierno, asegurando la puesta en marcha de las acciones planteadas en la estrategia. En este marco, se reconocen tres espacios fundamentales de articulación:

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8.order-lg-1.order-2(data-aos="fade-right")
         AcordionA.color-acento-botones(tipo="b" clase-tarjeta="tarjeta BG03" data-aos="zoom-in")
          div(titulo="Nación-territorio")
            p.mb-0 Orientado a la coordinación entre el nivel nacional y las entidades territoriales para fortalecer la implementación de acciones psicosociales, unificar lineamientos y garantizar que las orientaciones técnicas se adapten a las realidades locales.
          div(titulo="Intersectorial")
            p.mb-0 Encaminado a promover el trabajo conjunto entre sectores con competencia en la atención a población migrante y colombiana retornada. Este espacio facilita la focalización de comunidades de acogida, la identificación de la oferta institucional disponible, la derivación de casos y el intercambio de avances y retos en los procesos de acompañamiento psicosocial.
          div(titulo="Articulación con la Atención Integral en Salud")
            p.mb-0 Fundamentada en una visión integral del bienestar. Se reconoce que la salud mental está estrechamente vinculada a las condiciones sociales, familiares y comunitarias, por lo que la atención psicosocial debe coordinarse con las rutas de salud pública y los programas territoriales. El Ministerio de Salud y Protección Social lidera la formulación de políticas y lineamientos, mientras que las entidades territoriales son responsables de su adaptación e implementación.
      .col-lg-4.col-sm-6.col-8.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/tema2/img05.png' alt="Imagen decorativa")

    .row.justify-content-center.mb-5
      .col-lg-3.col-6.mb-lg-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/tema2/img06.svg' alt="Imagen decorativa")
      .col-lg-7(data-aos="fade-left")
        .bloque-texto-b.color-primario.p-4
          .bloque-texto-b__texto
            p Dentro de este marco de gobernanza, se integran disposiciones normativas que orientan la atención y la protección de la población migrante y retornada. Entre ellas se encuentran la Ley 1565 de 2012 (Ley del Retorno), que establece mecanismos para la reintegración de connacionales; el Decreto 216 de 2021, que reglamenta el Estatuto Temporal de Protección para Migrantes Venezolanos (ETPV); y el CONPES 4100 (DNP, 2022), que define estrategias de gobernanza migratoria y prioriza el bienestar psicosocial y la integración comunitaria.
            p.mb-0 A su vez, la cooperación técnica del ACNUR y la OIM fortalece las capacidades institucionales mediante la transferencia de conocimientos, el apoyo técnico y la promoción de buenas prácticas, contribuyendo a que los territorios implementen procesos psicosociales sostenibles y culturalmente pertinentes.

    p Este conjunto de esfuerzos articulados permite consolidar un sistema de acompañamiento psicosocial que responde a las necesidades reales de la población, evita la duplicación de acciones y garantiza intervenciones integrales y coordinadas en todos los niveles.

</template>

<script>
export default {
  name: 'Tema2',
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
