<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    p Este componente ofrece una visión completa sobre la Estrategia Integral de Acompañamiento Psicosocial en contextos de movilidad humana. Presenta sus conceptos fundamentales, los enfoques que orientan la intervención, los actores involucrados y las etapas que guían el proceso de acompañamiento. También aborda las herramientas metodológicas y el marco normativo que respalda la atención psicosocial, permitiendo comprender cómo se articula la respuesta institucional frente a las necesidades de la población migrante y retornada.
    p.mb-5 Para comprender la importancia del contenido y los temas abordados, se recomienda acceder al siguiente video:

    figure(data-aos="zoom-in")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/vdPrCjWJSHo?si=X4NxENRo3LLXAua_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
