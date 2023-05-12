<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(data-aos="fade-right")(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.svg')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0 Desarrollo de videojuegos y entornos interactivos
          
          .h2 Información del programa
          .banner-principal__datos
            ul
              li.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Desarrollo de videojuegos y entornos interactivos
              li.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 228108
              li.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Total Horas: 
                p.banner-principal__datos__item__texto 3984 horas lectivas
              li.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Duración en semanas: 
                p.banner-principal__datos__item__texto 27 meses
              li.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto virtual
        .d-none.d-lg-block.col-lg-5
          .video
            | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/5lPd98N0lOg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación
    p En este programa se aprenderá a desarrollar videojuegos y entornos interactivos, partiendo desde cero, pasando por las fases de preproducción, producción y posproducción. Comenzando por la historia y tipos de videojuegos, para poder desarrollar la idea base, elaborar el guión narrativo, guión técnico, storyboard y definir las mecánicas y niveles del juego.
      br
      br
      | Posterior a ello se conocerán los conceptos básicos de artes para afianzar las bases creativas y comenzar a diseñar todo el arte conceptual, el proceso de creación de personajes, objetos y el entorno. Utilizando software libre como Blender para el modelado 3D, texturizado, rigging y animación, elementos que después serán integrados en Unity 3D, para la programación del videojuego donde se crearán los diferentes niveles y escenarios. 
      br
      br
      | Para que el videojuego tenga un correcto funcionamiento y sea realmente divertido, se diseñarán sus sistemas de dinámicas, mecánicas y estéticas, buscando mantener el interés emocional hacia el juego, así como las motivaciones para asumir retos.  Determinando así, la funcionalidad básica del videojuego y todas las acciones y eventos que le permitirán al jugador, lograr cumplir con las metas y retos. 
      br
      br
      | Se conocerán fundamentos de programación orientada a objetos, la funcionalidad del motor de videojuegos, la dinámica y procesos de integración de recursos al motor y la forma como podemos conectar archivos de código a dichos recursos. Después se adentrará en el diseño lógico del videojuego y la comprensión y manejo de la interfaz de programación de Unity3D y el lenguaje de programación C-Sharp.
      br
      br
      | Se aplicarán métodos de prueba y testeo que facilitarán el correcto manejo, corrección de errores y optimización en las diferentes dimensiones del videojuego, como son el arte, la interfaz, las mecánicas, la funcionalidad y el sonido.
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-right")
    .titulo__template--a.mb-4
      span.h4 2. Justificación<br>del programa
    p En el ámbito internacional, existen estudios que revelan que el déficit de la formación del recurso humano, es una de las principales barreras identificadas para el crecimiento de un sector competitivo en los países en desarrollo. Respecto a esto, en muchas naciones existe una carencia importante de profesionales en desarrollo de videojuegos y especialistas de áreas afines a las Tecnologías de la Información y la Comunicación (TIC). El problema principal en estos países, lo que podría aplicarse también para Colombia, es que la demanda potencial de la industria supera la oferta local de mano de obra calificada, a un ritmo que puede retrasar su crecimiento, especialmente hacia los mercados externos.
      br
      br
      | Dadas las proyecciones, después de 2016 el problema de la escasez de talento de TI crece exponencialmente y no puede resolverse fácilmente. Por lo tanto, desde la visión del programa de formación se pretende resolver esta problemática.
      br
      br
      | Lo anterior, demuestra claramente la necesidad existente y futura de formación de personal en tecnologías relacionadas con el sector de las TIC, las cuales han sido identificadas hacia la programación de videojuegos, gestión y manipulación de contenidos digitales sobre redes y plataformas digitales, fijas, móviles y convergentes, SCRUM, así como reforzar conocimiento en áreas como administración de proyectos y habilidades en analíticas, fortaleciendo las habilidades blandas en áreas como el arte y diseño, contenidos 2D/3D, la comunicación, trabajo en equipo, interacción con clientes, inglés y negocios.
      br
      br
      | El SENA ofrece el programa de formación tecnólogo en desarrollo de videojuegos y entornos interactivos con todos los elementos de formación profesionales, sociales, tecnológicos y culturales, aportando como elementos diferenciadores de valor agregado metodologías de aprendizaje innovadoras, el acceso a tecnologías de última generación y una estructuración sobre métodos más que contenidos, lo que potencia la formación de ciudadanos librepensadores, con capacidad crítica, solidaria y emprendedora.
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-left")
    .titulo__template--a.mb-4
      span.h4 3. Competencias a<br>desarrollar

    ul.lista-ul--color
      li 
        i.lista-ul__vineta
        | Aplicación de conocimientos de las ciencias naturales de acuerdo con situaciones del contexto productivo y social (220201501).
      li 
        i.lista-ul__vineta
        | Aplicar prácticas de protección ambiental, seguridad y salud en el trabajo de acuerdo con las políticas organizacionales y la normatividad vigente (220601501).
      li 
        i.lista-ul__vineta
        | Desarrollar procesos de comunicación eficaces y efectivos, teniendo en cuenta situaciones de orden social, personal y (240201524).
      li 
        i.lista-ul__vineta
        | Ejercer derechos fundamentales del trabajo en el marco de la constitución política y los convenios internacionales (210201501).
      li 
        i.lista-ul__vineta
        | Interactuar en el contexto productivo y social de acuerdo con principios éticos para la construcción de una cultura de paz (240201526).
      li 
        i.lista-ul__vineta
        | Generar hábitos saludables de vida mediante la aplicación de programas de actividad física en los contextos productivos y sociales (230101507).
      li 
        i.lista-ul__vineta
        | Gestionar procesos propios de la cultura emprendedora y empresarial de acuerdo con el perfil personal y los requerimientos de los contextos productivo y social (240201529).
      li 
        i.lista-ul__vineta
        | Implementar componentes de arte y audio de acuerdo con el diseño del videojuego y herramientas de desarrollo (220501089).
      li 
        i.lista-ul__vineta
        | Interactuar en lengua inglesa de forma oral y escrita dentro de contextos sociales y laborales según los criterios establecidos por el marco común europeo de referencia para las lenguas (240202501).
      li 
        i.lista-ul__vineta
        | Orientar investigación formativa según referentes técnicos (240201064).
      li 
        i.lista-ul__vineta
        | Planear el videojuego de acuerdo con procedimientos y requisitos técnicos (220501087).
      li 
        i.lista-ul__vineta
        | Probar el videojuego de acuerdo con el procedimiento técnico y herramientas de desarrollo (220501090).
      li 
        i.lista-ul__vineta
        | Producir la lógica del videojuego de acuerdo con el diseño y técnicas de desarrollo (220501088).
      li 
        i.lista-ul__vineta
        | Razonar cuantitativamente frente a situaciones susceptibles de ser abordadas de manera matemática en contextos laborales, sociales y personales (240201528).
      li 
        i.lista-ul__vineta
        | Resultado del aprendizaje de la inducción (240201530).
      li 
        i.lista-ul__vineta
        | Resultados de aprendizaje etapa practica (999999999).
      li 
        i.lista-ul__vineta
        | Utilizar herramientas informáticas de acuerdo con las necesidades de manejo de información (220501046).
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-right")
    .titulo__template--a.mb-4
      span.h4 4. Perfil de<br>ingreso

    ul.lista-ul--color
      li 
        i.lista-ul__vineta
        | Nivel académico adecuado de: media académica con certificación en grado 11.
      li 
        i.lista-ul__vineta
        | Edad mínima definida en la ley: 14 años.
      li 
        i.lista-ul__vineta
        | Requisitos adicionales: presentar resultado de la prueba o examen de estado de la educación media.
      li 
        i.lista-ul__vineta
        | Aspectos actitudinales, motivacionales y de interés: capacidad de automotivación, autocontrol y autogestión. Actitud positiva, frente al entorno y la interacción social. Solucionador de problemas y resolver conflictos, receptivo o vocación a los procesos de servicios de tecnología.
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-left")
    .titulo__template--a.mb-4
      span.h4 5. Perfil de<br>egreso
    p.mb-5 El tecnólogo en desarrollo de videojuegos y entornos interactivos está capacitado para generar el código que definirá el comportamiento de cada elemento del videojuego (Personajes, objetos, interfaces gráficas de usuario etc.) y la interacción del videojuego con el jugador. También comprende de manera clara las fases de su diseño y todos sus componentes, como la experiencia de usuario, la usabilidad, la narrativa, etc. Incorpora los recursos audiovisuales, que le brindarán un orden lógico al proceso de producción, asegurando de manera efectiva el proyecto en toda su extensión. Igualmente está en capacidad de realizar pruebas para que los productos cumplan con todos los estándares y necesidades del mercado, promoviendo el trabajo en equipo y el respeto en el ámbito laboral y profesional.
      br
      br
      | Principales productos del trabajo del egresado:

    ul.lista-ul--color
      li 
        i.lista-ul__vineta
        | Documentación interpretativa del código.
      li 
        i.lista-ul__vineta
        | Código fuente de la programación de la interactividad de acuerdo con el diseño del videojuego.
      li 
        i.lista-ul__vineta
        | Prototipos de prueba del juego.
      li 
        i.lista-ul__vineta
        | Videojuego.
      li 
        i.lista-ul__vineta
        | Informe de pruebas realizadas.
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-down")
    .titulo__template--a.mb-4
      span.h4 6. Estrategia<br>metodologíca
    p.mb-5 Centrada en la construcción de autonomía para garantizar la calidad de la formación en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportadas en el utilización de las tecnologías de la información y la comunicación, integradas, en ambientes virtuales de aprendizaje, que en todo caso recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias. 
      br
      br
      | Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el que hacer y los resultados de aprendizaje que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:
    .row.g-4.justify-content-center
      .col-5.col-sm-3.col-md-2
        figure.mb-2
          img.w-75.mx-auto(src='@/assets/curso/01.svg', alt='El instructor - tutor')
        p.text-center
          strong El instructor - tutor
      .col-5.col-sm-3.col-md-2
        figure.mb-2
          img.w-75.mx-auto(src='@/assets/curso/02.svg', alt='El entorno')
        p.text-center
          strong El entorno
      .col-5.col-sm-3.col-md-2
        figure.mb-2
          img.w-75.mx-auto(src='@/assets/curso/03.svg', alt='Las TIC')
        p.text-center
          strong Las TIC
      .col-5.col-sm-3.col-md-2
        figure.mb-2
          img.w-75.mx-auto(src='@/assets/curso/04.svg', alt='El trabajo colaborativo')
        p.text-center
          strong El trabajo colaborativo
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-right")
    .titulo__template--a.mb-4
      span.h4 Créditos
    .creditos
      div(
        v-for="(creditoKey, index) of Object.keys(creditosData)"
        :class="index != Object.keys(creditosData).length -1 ? 'mb-4' : ''" 
      )
        .creditos__titulo {{configTitulos[creditoKey]}}
        table
          tbody
            tr(
              v-for="(item, idx) of creditosData[creditoKey]" 
              :key="creditoKey+idx"
            )
              td.text-bold(colspan='2' v-html="renderText(item.nombre)")
              td(colspan='2' v-html="renderText(item.cargo)")
              td(colspan='3' v-html="renderText(item.centro)")
  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({
    configTitulos: {
      liderEquipo: 'ECOSISTEMA DE RECURSOS EDUCATIVOS DIGITALES',
      contenidoInstruccional: 'CONTENIDO INSTRUCCIONAL',
      desarrolloProducto:
        'DISEÑO Y DESARROLLO DE RECURSOS EDUCATIVOS DIGITALES',
      gestoresRepositorio: 'GESTORES DE REPOSITORIO',
    },
  }),
  computed: {
    creditosData() {
      return this.$config.creditos
    },
  },
  methods: {
    renderText(textObj) {
      let newText = ''
      if (Array.isArray(textObj)) {
        textObj.forEach((texto, index) => {
          newText += (index ? '<br/>' : '') + texto
        })
      } else {
        newText += textObj
      }
      return newText
    },
  },
}
</script>

<style lang="sass">
.creditos
  td, th
    border-color: $color-sistema-c
</style>
