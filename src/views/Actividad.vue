<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(icono="far fa-question-circle" titulo="Actividad didáctica")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
  
      #Actividad                
        <Actividad :cuestionario="cuestionario"/>
  
  </template>

<script>
export default {
  name: 'ActividadDidactica',
  data: () => ({
    cuestionario: {
      tema: 'tema_actividad_didactica',
      titulo: 'Cuestionario',
      introduccion: 'texto_introductorio_actividad_didactica',
      barajarPreguntas: true,
      preguntas: [
        {
          id: 1,
          texto:
            'La Estrategia Integral de Acompañamiento Psicosocial, busca garantizar la atención y el bienestar emocional de la población migrante.',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: true },
            { id: 'b', texto: 'Falso', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión de los fundamentos, etapas y marco normativo de la estrategia de acompañamiento psicosocial para población migrante, así como de su aplicación práctica.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 2,
          texto:
            'La fase de diagnóstico en la intervención psicosocial se desarrolla después del seguimiento.',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: false },
            { id: 'b', texto: 'Falso', esCorrecta: true },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión de los fundamentos, etapas y marco normativo de la estrategia de acompañamiento psicosocial para población migrante, así como de su aplicación práctica.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 3,
          texto:
            'La dignidad humana, es uno de los principios de la estrategia.',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: true },
            { id: 'b', texto: 'Falso', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión de los fundamentos, etapas y marco normativo de la estrategia de acompañamiento psicosocial para población migrante, así como de su aplicación práctica.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 4,
          texto:
            'La Ley 2136 de 2021 corresponde a la Política Nacional de Salud Mental.',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: false },
            { id: 'b', texto: 'Falso', esCorrecta: true },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión de los fundamentos, etapas y marco normativo de la estrategia de acompañamiento psicosocial para población migrante, así como de su aplicación práctica.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 5,
          texto:
            'La articulación interinstitucional es fundamental para garantizar la efectividad del acompañamiento psicosocial.',
          imagen: require('@/assets/actividad/imagen5.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: true },
            { id: 'b', texto: 'Falso', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión de los fundamentos, etapas y marco normativo de la estrategia de acompañamiento psicosocial para población migrante, así como de su aplicación práctica.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 6,
          texto:
            'La fase de seguimiento en la estrategia permite evaluar la sostenibilidad del proceso psicosocial.',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: true },
            { id: 'b', texto: 'Falso', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión de los fundamentos, etapas y marco normativo de la estrategia de acompañamiento psicosocial para población migrante, así como de su aplicación práctica.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 7,
          texto:
            'El enfoque de género y de ciclo vital no se aplica en la atención psicosocial.',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: false },
            { id: 'b', texto: 'Falso', esCorrecta: true },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión de los fundamentos, etapas y marco normativo de la estrategia de acompañamiento psicosocial para población migrante, así como de su aplicación práctica.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 8,
          texto:
            'El CONPES 4100 de 2022 orienta la gestión migratoria y la coordinación institucional.',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: true },
            { id: 'b', texto: 'Falso', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión de los fundamentos, etapas y marco normativo de la estrategia de acompañamiento psicosocial para población migrante, así como de su aplicación práctica.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 9,
          texto:
            'Las herramientas psicosociales incluyen talleres, grupos de apoyo, círculos de palabra, entre otros.',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: true },
            { id: 'b', texto: 'Falso', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión de los fundamentos, etapas y marco normativo de la estrategia de acompañamiento psicosocial para población migrante, así como de su aplicación práctica.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 10,
          texto:
            'El acompañamiento psicosocial se desarrolla solo en contextos institucionales, sin participación comunitaria.',
          imagen: require('@/assets/actividad/imagen5.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: false },
            { id: 'b', texto: 'Falso', esCorrecta: true },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión de los fundamentos, etapas y marco normativo de la estrategia de acompañamiento psicosocial para población migrante, así como de su aplicación práctica.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 11,
          texto:
            'La Estrategia Integral de Acompañamiento Psicosocial se constituye como un eje esencial dentro de las _______ públicas dirigidas a la población migrante, retornada y de acogida.',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'políticas', esCorrecta: true },
            { id: 'b', texto: 'actividades', esCorrecta: false },
            { id: 'c', texto: 'festividades', esCorrecta: false },
            { id: 'd', texto: 'conferencias', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión de los fundamentos, etapas y marco normativo de la estrategia de acompañamiento psicosocial para población migrante, así como de su aplicación práctica.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 12,
          texto:
            'La intervención psicosocial se desarrolla a partir de las fases de diagnóstico, intervención y ________, asegurando continuidad y sostenibilidad.',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'planificación', esCorrecta: false },
            { id: 'b', texto: 'actuación', esCorrecta: false },
            { id: 'c', texto: 'seguimiento', esCorrecta: true },
            { id: 'd', texto: 'capacitación', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión de los fundamentos, etapas y marco normativo de la estrategia de acompañamiento psicosocial para población migrante, así como de su aplicación práctica.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 13,
          texto:
            'La estrategia se fundamenta en principios universales como la dignidad humana, la equidad, la participación social, la __________ y la inclusión.',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'perspectiva', esCorrecta: false },
            { id: 'b', texto: 'atención', esCorrecta: false },
            { id: 'c', texto: 'interculturalidad', esCorrecta: true },
            { id: 'd', texto: 'acción', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión de los fundamentos, etapas y marco normativo de la estrategia de acompañamiento psicosocial para población migrante, así como de su aplicación práctica.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 14,
          texto:
            'El Decreto 0729 de 2025, que reglamenta la Política Nacional de ______ Mental, dispone que la atención psicosocial debe integrarse en los Planes Territoriales de Salud.',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Bienestar', esCorrecta: false },
            { id: 'b', texto: 'Salud', esCorrecta: true },
            { id: 'c', texto: 'Cuidado', esCorrecta: false },
            { id: 'd', texto: 'Equidad', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión de los fundamentos, etapas y marco normativo de la estrategia de acompañamiento psicosocial para población migrante, así como de su aplicación práctica.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 15,
          texto:
            'El marco normativo que respalda la Estrategia Integral de Acompañamiento Psicosocial Migratorio reúne políticas, ________, decretos y guías técnicas.',
          imagen: require('@/assets/actividad/imagen5.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'leyes', esCorrecta: true },
            { id: 'b', texto: 'actividades', esCorrecta: false },
            { id: 'c', texto: 'reuniones', esCorrecta: false },
            { id: 'd', texto: 'estrategias', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión de los fundamentos, etapas y marco normativo de la estrategia de acompañamiento psicosocial para población migrante, así como de su aplicación práctica.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 16,
          texto:
            '¿Cuál es el propósito principal de la Estrategia Integral de Acompañamiento Psicosocial?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Orientar la intervención desde un enfoque humano, integral y participativo.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Realizar seguimiento a normas internacionales.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Promover actividades recreativas y culturales.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Ofrecer servicios de salud física únicamente.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión de los fundamentos, etapas y marco normativo de la estrategia de acompañamiento psicosocial para población migrante, así como de su aplicación práctica.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 17,
          texto:
            '¿Cuál es la primera fase del proceso de intervención psicosocial?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Diagnóstico.', esCorrecta: true },
            { id: 'b', texto: 'Intervención.', esCorrecta: false },
            { id: 'c', texto: 'Seguimiento.', esCorrecta: false },
            { id: 'd', texto: 'Evaluación.', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión de los fundamentos, etapas y marco normativo de la estrategia de acompañamiento psicosocial para población migrante, así como de su aplicación práctica.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 18,
          texto: '¿Qué es el PAPSIVI?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Programa Audiovisual Participativo de Salud.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Programa de Atención y Salud Integral a Víctimas.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Programa de Atención Psicosocial y Salud Integral a Víctimas.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Preparación Activa de Salud Mental para las Víctimas. ',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión de los fundamentos, etapas y marco normativo de la estrategia de acompañamiento psicosocial para población migrante, así como de su aplicación práctica.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 19,
          texto:
            '¿Qué entidad lidera la formulación de lineamientos para la atención psicosocial en Colombia?',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Ministerio de Educación Nacional.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Organización Panamericana de la Salud.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Ministerio de Salud y Protección Social.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Departamento Nacional de Planeación.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión de los fundamentos, etapas y marco normativo de la estrategia de acompañamiento psicosocial para población migrante, así como de su aplicación práctica.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 20,
          texto:
            '¿Cuál documento define las estrategias nacionales para la gestión migratoria y la articulación interinstitucional?',
          imagen: require('@/assets/actividad/imagen5.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'CONPES 4100 de 2022.', esCorrecta: true },
            { id: 'b', texto: 'Ley 2460 de 2025.', esCorrecta: false },
            { id: 'c', texto: 'Decreto 0729 de 2025.', esCorrecta: false },
            { id: 'd', texto: 'Ley 1565 de 2012.', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión de los fundamentos, etapas y marco normativo de la estrategia de acompañamiento psicosocial para población migrante, así como de su aplicación práctica.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
      ],
      mensaje_final_aprobado:
        'Ha superado la actividad y demuestra sólidos conocimientos sobre el componente formativo.',
      mensaje_final_reprobado:
        'No ha superado la actividad. Le recomendamos volver a revisar el componente formativo e intentar nuevamente la actividad didáctica.',
    },
  }),
}
</script>
