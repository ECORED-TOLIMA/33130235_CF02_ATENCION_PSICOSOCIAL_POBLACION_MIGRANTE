<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="fade-right")
      .titulo-principal__numero
        span 1
      h1 Fundamentos de la Estrategia Integral de Acompañamiento Psicosocial
    
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/img01.jpg')})`}" data-aos="fade-right"
      )
      .bloque-texto-g__texto.p-4(data-aos="fade-left")
        p.mb-0 La Estrategia Integral de Acompañamiento Psicosocial se constituye como un eje esencial dentro de las políticas públicas dirigidas a la población migrante, retornada y de acogida. Su propósito consiste en orientar la intervención desde un enfoque humano, integral y participativo, que responde a las necesidades emocionales, sociales y culturales derivadas de los procesos de movilidad humana (Ministerio de Salud y Protección Social, 2023).
    
    p.mb-5 Desde esta perspectiva, la estrategia impulsa la reconstrucción de redes de apoyo, la adaptación cultural y la inclusión comunitaria, reconociendo que estos elementos resultan fundamentales para garantizar el bienestar psicosocial y el restablecimiento de derechos. También promueve el fortalecimiento de capacidades individuales y colectivas, entendiendo la migración como un proceso que involucra transformaciones profundas en la vida de las personas y en las dinámicas comunitarias.

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-6.order-lg-1.order-2(data-aos="fade-right")
        .cajon.color-primario.p-4.mb-4
          p.mb-0 Comprender los fundamentos de esta estrategia implica analizar sus principios orientadores, sus objetivos y los actores responsables de su implementación. Estos componentes permiten articular la acción interinstitucional con los lineamientos internacionales en salud mental, protección integral y derechos humanos, incluidos los marcos establecidos por organismos como ACNUR, OIM y la OMS.
        p.mb-0 Desde este marco conceptual, se reconoce la importancia de la cooperación entre el Estado, los organismos internacionales, las entidades territoriales y las comunidades locales. Esta articulación resulta fundamental para consolidar respuestas integrales, sostenibles y con enfoque diferencial, que permitan acompañar a la población migrante respetando su dignidad, diversidad y trayectoria de vida.
      .col-lg-4.col-sm-6.col-8.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/tema1/img02.png' alt="Imagen decorativa")

    separador
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.1 Concepto y objetivos de la estrategia
    
    p.mb-5 La Estrategia Integral de Acompañamiento Psicosocial Migratorio se entiende como un conjunto articulado de acciones orientadas a promover el bienestar emocional, social y comunitario de las personas migrantes, retornadas y de las comunidades de acogida. Esta estrategia busca fortalecer la salud mental, favorecer la integración social y garantizar el restablecimiento de derechos mediante intervenciones fundamentadas en la resiliencia, la participación y la corresponsabilidad institucional (Ministerio de Salud y Protección Social, 2023).

    .row.justify-content-center.mb-5
      .col-lg-4.col-sm-6.col-8.mb-lg-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/tema1/img03.png' alt="Imagen decorativa")
      .col-lg-8(data-aos="fade-left")
        p De acuerdo con la Organización Internacional para las Migraciones (OIM, 2019), las estrategias psicosociales en contextos de movilidad humana deben centrarse tanto en las necesidades individuales como en las colectivas, promoviendo la reconstrucción del tejido social y la cohesión comunitaria.
        .cajon.color-primario.p-4
          p.mb-0 El Ministerio de Salud y Protección Social (2021) señala que estas acciones se articulan con la Política Nacional de Salud Mental, adoptada mediante la Resolución 4886 de 2018 y con la Ley Estatutaria de Salud (Ley 1751 de 2015), garantizando la atención integral, el enfoque diferencial y el trabajo intersectorial. Asimismo, se relacionan con la Política de Atención Integral en Salud establecida en la Resolución 429 de 2016, la cual reconoce la salud como un derecho fundamental.

    .row.justify-content-center.mb-5
      .col-lg-10
        .titulo-sexto.color-acento-contenido(data-aos="fade-right")
          h5 Figura 1.
          i Estructura de la Estrategia Integral de Acompañamiento Psicosocial
        figure(data-aos="zoom-in")
          img.d-lg-flex.d-none(src='@/assets/curso/tema1/img04.svg' alt="En la figura 1 se presenta la estructura de la Estrategia Integral de Acompañamiento Psicosocial, organizada en tres niveles: fundamentos conceptuales, principios orientadores y actores involucrados, que incluyen la cooperación internacional, la comunidad y la sociedad civil.")
          img.d-lg-none.d-flex(src='@/assets/curso/tema1/img05.svg' alt="En la figura 1 se presenta la estructura de la Estrategia Integral de Acompañamiento Psicosocial, organizada en tres niveles: fundamentos conceptuales, principios orientadores y actores involucrados, que incluyen la cooperación internacional, la comunidad y la sociedad civil.")

    p A partir del marco conceptual y la figura presentada, la estrategia orienta sus acciones hacia los siguientes objetivos:

    .row.justify-content-center.mb-5
      .col-lg-4.col-sm-10.mb-4(data-aos="fade-right")
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img06.svg' alt="Imagen decorativa")
          .tarjeta.BG02.p-4
            p.text-center.mt-4.mb-0 Promover el bienestar psicosocial mediante intervenciones que fortalezcan la salud mental y el equilibrio emocional de las personas migrantes y sus comunidades.
      .col-lg-4.col-sm-10.mb-4(data-aos="flip-up")
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img07.svg' alt="Imagen decorativa")
          .tarjeta.BG02.p-4
            p.text-center.mt-4.mb-0 Fomentar la inclusión social, facilitando procesos de adaptación cultural, fortalecimiento de lazos comunitarios y participación activa en los entornos de acogida.
      .col-lg-4.col-sm-10.mb-4(data-aos="fade-left")
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img08.svg' alt="Imagen decorativa")
          .tarjeta.BG02.p-4
            p.text-center.mt-4.mb-0 Garantizar el enfoque de derechos humanos, asegurando que la atención psicosocial reconozca la dignidad, autonomía y diversidad de las personas.
      .col-lg-4.col-sm-10.mb-4(data-aos="fade-right")
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img09.svg' alt="Imagen decorativa")
          .tarjeta.BG02.p-4
            p.text-center.mt-4.mb-0 Aplicar principios orientadores, como el enfoque diferencial, la interculturalidad y la integralidad, para asegurar una atención pertinente y adaptada a las particularidades de cada grupo poblacional.
      .col-lg-4.col-sm-10.mb-4(data-aos="fade-left")
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img10.svg' alt="Imagen decorativa")
          .tarjeta.BG02.p-4
            p.text-center.mt-4.mb-0 Fortalecer la corresponsabilidad entre actores como organismos internacionales, sociedad civil y comunidad, para consolidar respuestas articuladas, sostenibles y coherentes con los lineamientos nacionales e internacionales.

    separador
    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.2 Principios y enfoques que orientan la intervención
    
    p.mb-5 La estrategia se fundamenta en principios universales como la dignidad humana, la equidad, la participación social, la interculturalidad y la inclusión. Estos principios orientan las acciones hacia una atención integral, asegurando que cada persona reciba acompañamiento acorde con sus condiciones particulares y su contexto cultural.

    TabsB.color-acento-botones.mb-5(data-aos="zoom-out")
      .BGIMG01.py-lg-5.py-4.px-4(titulo="Dignidad humana" :icono="require('@/assets/curso/tema1/img11.svg')")
        .row.justify-content-center
          .col-lg-7.col-10.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img11.jpg' alt="Imagen decorativa")
          .col-lg-5
            p.mb-0 Es el fundamento de los derechos humanos y un valor superior que reconoce el valor inherente de cada individuo por el simple hecho de ser humano, independientemente de su origen, condición social o cualquier otra característica (Ministerio de Salud y Protección Social, 2014).
      .BGIMG01.py-lg-5.py-4.px-4(titulo="Equidad" :icono="require('@/assets/curso/tema1/img12.svg')")
        .row.justify-content-center
          .col-lg-7.col-10.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img12.jpg' alt="Imagen decorativa")
          .col-lg-5
            p.mb-0 Hace referencia a las acciones y procesos orientados a garantizar la igualdad de oportunidades y resultados, reconociendo las diferencias y las desventajas existentes (Organización de los Estados Americanos, 2015).
      .BGIMG01.py-lg-5.py-4.px-4(titulo="Participación social" :icono="require('@/assets/curso/tema1/img13.svg')")
        .row.justify-content-center
          .col-lg-7.col-10.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img13.jpg' alt="Imagen decorativa")
          .col-lg-5
            p.mb-0 Implica que los individuos y las comunidades asuman un rol activo y protagónico en la toma de decisiones y en la formulación e implementación de políticas y programas que inciden en su vida cotidiana (Defensoría del Pueblo, 2022).
      .BGIMG01.py-lg-5.py-4.px-4(titulo="Interculturalidad" :icono="require('@/assets/curso/tema1/img14.svg')")
        .row.justify-content-center
          .col-lg-7.col-10.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img14.jpg' alt="Imagen decorativa")
          .col-lg-5
            p.mb-0 Enfoque que promueve el reconocimiento y valoración de las diversas culturas presentes en un territorio, fomentando el respeto mutuo, la cooperación y el intercambio equitativo entre ellas.
      .BGIMG01.py-lg-5.py-4.px-4(titulo="Inclusión" :icono="require('@/assets/curso/tema1/img15.svg')")
        .row.justify-content-center
          .col-lg-7.col-10.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img15.jpg' alt="Imagen decorativa")
          .col-lg-5
            p.mb-0 Es un proceso orientado a garantizar que todas las personas, sin importar sus diferencias, tengan acceso a las mismas oportunidades y puedan participar plenamente en la vida social (Ministerio de Educación Nacional, 2020).

    p.mb-5 En el marco del acompañamiento psicosocial, resulta indispensable el reconocimiento y la apropiación de los enfoques que orientan las acciones dirigidas a la población migrante, retornada y a las comunidades de acogida. Estos enfoques ofrecen criterios conceptuales y operativos que permiten comprender las particularidades de cada persona, abordar adecuadamente los efectos de la migración y garantizar intervenciones integrales, respetuosas y contextualizadas. Su aplicación orienta la toma de decisiones y fortalece la calidad de los procesos de acompañamiento.

    .tarjeta.BGIMG02.p-4.mb-5(data-aos="zoom-in")
      SlyderA.color-acento-botones.arrow-white(tipo="b")
        .row.justify-content-center
          .col-lg-4.order-lg-1.order-2
            .h4 Enfoque psicosocial
            p.mb-0 Se reconoce como un enfoque transversal en los procesos de atención y acompañamiento a personas, familias y comunidades vulnerables. Está orientado a comprender los efectos de la experiencia migratoria, dar lugar a las vivencias, facilitar el procesamiento emocional y promover el fortalecimiento de los recursos de afrontamiento.
          .col-lg-8.col-10.order-1.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img16.jpg' alt="Imagen decorativa")
        .row.justify-content-center
          .col-lg-4.order-lg-1.order-2
            .h4 Enfoque de derechos humanos
            p.mb-0 Reconoce a los sujetos como titulares de derechos y orienta las políticas públicas hacia su garantía efectiva. En el contexto migratorio, invita a identificar las condiciones de vulnerabilidad presentes durante el tránsito, la llegada y la permanencia en el país de acogida, las cuales pueden estar acompañadas de situaciones de vulneración de derechos.
          .col-lg-8.col-10.order-1.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img17.jpg' alt="Imagen decorativa")
        .row.justify-content-center
          .col-lg-4.order-lg-1.order-2
            .h4 Enfoque diferencial
            p.mb-0 Es un método de análisis que permite comprender la situación de derechos y vulnerabilidad de diversos grupos poblacionales. Considera las particularidades individuales y colectivas con el fin de reconocer desigualdades, promover la no discriminación y garantizar intervenciones pertinentes que reconozcan la diversidad.
          .col-lg-8.col-10.order-1.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img18.jpg' alt="Imagen decorativa")
        .row.justify-content-center
          .col-lg-4.order-lg-1.order-2
            .h4 Enfoque de género
            p.mb-0 Permite analizar las relaciones de poder entre géneros y visibilizar desigualdades y discriminaciones. Su incorporación implica adoptar estrategias metodológicas que favorezcan la equidad, identifiquen imaginarios sociales y garanticen la participación efectiva de mujeres, hombres y personas con identidades diversas en los procesos de acompañamiento psicosocial.
          .col-lg-8.col-10.order-1.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img19.jpg' alt="Imagen decorativa")
        .row.justify-content-center
          .col-lg-4.order-lg-1.order-2
            .h4 Enfoque étnico
            p.mb-0 Sustentado en la Constitución Política de 1991, reconoce al país como pluriétnico y multicultural. Este enfoque afirma la diversidad cultural, el derecho al territorio, la autonomía y el autorreconocimiento de los pueblos, así como sus formas particulares de comprender el mundo y el vínculo con la ancestralidad.
          .col-lg-8.col-10.order-1.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img20.jpg' alt="Imagen decorativa")
        .row.justify-content-center
          .col-lg-4.order-lg-1.order-2
            .h4 Enfoque de movilidad humana
            p.mb-0 Promueve la formulación de políticas públicas que respondan de manera integral a los fenómenos asociados a la movilidad humana, considerando las necesidades de las personas migrantes y de las comunidades receptoras.
          .col-lg-8.col-10.order-1.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img21.jpg' alt="Imagen decorativa")
        .row.justify-content-center
          .col-lg-4.order-lg-1.order-2
            .h4 Enfoque de acción sin daño
            p.mb-0 Busca que las acciones desarrolladas se fundamenten en un análisis ético que minimice la posibilidad de generar afectaciones involuntarias. Reconoce que ningún profesional está exento de generar daño y promueve prácticas responsables y conscientes.
          .col-lg-8.col-10.order-1.mb-lg-0.mb-4
            img(src='@/assets/curso/tema1/img22.jpg' alt="Imagen decorativa")

    separador
    #t_1_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.3 Actores institucionales y comunitarios
    
    p.mb-5 El acompañamiento psicosocial en contextos de movilidad humana requiere la participación articulada de diversos actores institucionales y comunitarios. Cada uno aporta funciones complementarias que permiten garantizar una atención integral, oportuna y contextualizada para la población migrante, colombiana retornada y comunidades de acogida. Esta coordinación asegura la protección de derechos, la gestión adecuada de riesgos y el fortalecimiento del bienestar emocional y social. A continuación, se presentan los actores que se involucran en este proceso:

    .mb-4.d-flex(data-aos="fade-right")
      .d-flex.flex-wrap.align-items-center.pe-4.tarjeta.color-secundario(style="border-radius: 20px;")
        img(src='@/assets/curso/temas/img01.svg' style="max-width: 32px; margin-left: -16px;")
        h3.col.ps-3.mb-0 Actores institucionales
    
    .BGIMG03.px-md-5.px-4.py-4.mb-5(data-aos="zoom-in")
      .tarjeta.tarjeta--blanca.p-4
        PasosB.color-acento-botones
          .row.justify-content-center
            .col-lg-6.order-lg-1.order-2
              .h4 Ministerio de Salud y Protección Social (MSPS)
              p.mb-0 Actúa como entidad rectora del sistema de salud y define lineamientos técnicos y operativos para la atención psicosocial. A través de la Política Nacional de Salud Mental y los lineamientos para la atención en contextos de emergencia y movilidad humana, orienta la organización de servicios, la implementación de rutas y la adopción de enfoques diferenciales.
            .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
              img(src='@/assets/curso/tema1/img23.jpg' alt="Imagen decorativa")
          .row.justify-content-center
            .col-lg-6.order-lg-1.order-2
              .h4 Migración Colombia
              p.mb-0 Es responsable de la identificación, regularización y caracterización de la población migrante. Facilita el acceso a servicios de salud, protección y asistencia mediante estrategias como el Estatuto Temporal de Protección. Su labor es clave para la trazabilidad y el acompañamiento hacia la integración socioeconómica.
            .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
              img(src='@/assets/curso/tema1/img24.jpg' alt="Imagen decorativa")
          .row.justify-content-center
            .col-lg-6.order-lg-1.order-2
              .h4 Ministerio de Relaciones Exteriores
              p.mb-0 Lidera el Sistema Nacional de Migraciones, coordinando acciones intersectoriales, cooperación internacional y gestión territorial. Orienta procesos como retorno asistido, homologación de orientaciones técnicas y articulación con organismos locales e internacionales.
            .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
              img(src='@/assets/curso/tema1/img25.jpg' alt="Imagen decorativa")
          .row.justify-content-center
            .col-lg-6.order-lg-1.order-2
              .h4 Instituto Colombiano de Bienestar Familiar (ICBF)
              p.mb-0 Interviene en la protección de niños, niñas y adolescentes mediante equipos interdisciplinarios que implementan lineamientos de restablecimiento de derechos, fortalecimiento familiar y atención psicosocial con enfoque diferencial. Su participación es esencial en situaciones de riesgo o vulneración.
            .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
              img(src='@/assets/curso/tema1/img26.jpg' alt="Imagen decorativa")
          .row.justify-content-center
            .col-lg-6.order-lg-1.order-2
              .h4 Entidades territoriales (alcaldías, gobernaciones, secretarías de salud y desarrollo social)
              p.mb-0 Cumplen funciones operativas, adaptando las políticas nacionales al contexto territorial. Activan rutas integrales de atención, coordinan comités de migración y gestionan oferta institucional complementaria en salud pública, educación, protección y apoyo psicosocial comunitario.
            .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
              img(src='@/assets/curso/tema1/img27.jpg' alt="Imagen decorativa")
          .row.justify-content-center
            .col-lg-6.order-lg-1.order-2
              .h4 Organismos internacionales (OIM, ACNUR, OPS)
              p.mb-0 Brindan apoyo técnico y financiero, fortalecen capacidades institucionales y aportan metodologías y herramientas para la atención integral. Facilitan la transferencia de conocimientos y el fortalecimiento de las estrategias comunitarias.
            .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
              img(src='@/assets/curso/tema1/img28.jpg' alt="Imagen decorativa")
          .row.justify-content-center
            .col-lg-6.order-lg-1.order-2
              .h4 CONPES 4100 (DNP, 2022)
              p.mb-0 Resalta la importancia de la articulación entre Estado y sociedad civil para garantizar una atención sostenible e integral a la población migrante y retornada.
            .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
              img(src='@/assets/curso/tema1/img29.jpg' alt="Imagen decorativa")

    .mb-4.d-flex(data-aos="fade-right")
      .d-flex.flex-wrap.align-items-center.pe-4.tarjeta.color-secundario(style="border-radius: 20px;")
        img(src='@/assets/curso/temas/img01.svg' style="max-width: 32px; margin-left: -16px;")
        h3.col.ps-3.mb-0 Actores comunitarios
    
    .row.justify-content-center.mb-5
      .col-lg-11
        .tarjeta-avatar-b(data-aos="fade-right")
          .tarjeta-avatar-b__img(style="min-width: 10%; left: -3%")
            img(src='@/assets/curso/tema1/img30.svg' alt="Imagen decorativa")
          .tarjeta.BG01
            .p-4
              h4 Organizaciones comunitarias, líderes sociales y redes locales de apoyo
              p.mb-0 Facilitan la acogida de las personas, promueven la mediación cultural y permiten identificar tempranamente necesidades. Contribuyen al acompañamiento emocional, fomentan la participación social y fortalecen el tejido comunitario, desempeñando un papel clave en la promoción de la convivencia, la cohesión social y la creación de entornos protectores.

    p En conjunto, estos actores conforman una respuesta coordinada que reconoce las particularidades de la movilidad humana y promueve el bienestar psicosocial de todas las personas involucradas.

</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({}),
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
