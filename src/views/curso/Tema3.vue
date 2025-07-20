<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'3. Evaluación cualitativa y cuantitativa de riesgos'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema3/1.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        p.mb-5(data-aos="fade-left") La identificación y evaluación de peligros y riesgos en entornos industriales, constituye uno de los pilares fundamentales para garantizar la seguridad y salud de los trabajadores, la protección de los bienes materiales y la preservación del medio ambiente. En estos contextos complejos y dinámicos, donde interactúan múltiples procesos, sustancias y tecnologías, la gestión adecuada del riesgo se convierte en una necesidad ineludible.
    
        .bg-color-1.p-4(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema3/2.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Las industrias, como motores del desarrollo económico y tecnológico, deben adoptar un enfoque preventivo que les permita anticiparse a eventos no deseados, a través de metodologías sistemáticas y estructuradas. Esta gestión implica identificar peligros actuales y anticipar escenarios futuros, considerando modificaciones en procesos, incorporación de tecnologías y cambios operativos.
    
    h2(data-aos="fade-left") Identificación de peligros: primer paso crítico
    p.mb-5 La identificación de peligros es la etapa inicial de cualquier gestión de riesgos efectiva. Implica reconocer factores intrínsecos o extrínsecos capaces de causar daño en el entorno laboral. Para ello, se utilizan herramientas como: 
    
    .bg-full-width.bg-color-7
      .p-4.px-md-5
        .row.justify-content-center.align-items-stretch.mb-4
          .col-lg-3.mb-3.mb-lg-0
            .bg-color-6.p-4(data-aos="fade-left").h-100
              .row.align-items-center
                .col-lg-auto
                  img(src="@/assets/curso/tema3/3.svg", style="max-width: 90px").mx-auto
                .col-lg
                  h5.mb-2 01
                  p.mb-0 Observación directa.

          .col-lg-3.mb-3.mb-lg-0
            .bg-color-6.p-4(data-aos="fade-left").h-100
              .row.align-items-center
                .col-lg-auto
                  img(src="@/assets/curso/tema3/4.svg", style="max-width: 90px").mx-auto
                .col-lg
                  h5.mb-2 02
                  p.mb-0 Entrevistas con el personal.

          .col-lg-3.mb-3.mb-lg-0
            .bg-color-6.p-4(data-aos="fade-left").h-100
              .row.align-items-center
                .col-lg-auto
                  img(src="@/assets/curso/tema3/5.svg", style="max-width: 90px").mx-auto
                .col-lg
                  h5.mb-2 03
                  p.mb-0 Revisión documental.
          .col-lg-3.mb-3.mb-lg-0
            .bg-color-6.p-4(data-aos="fade-left").h-100
              .row.align-items-center
                .col-lg-auto
                  img(src="@/assets/curso/tema3/6.svg", style="max-width: 90px").mx-auto
                .col-lg
                  h5.mb-2 04
                  p.mb-0 <em>Checklists</em> (listas de verificación).
        p.mb-5 La participación activa de los trabajadores es esencial, debido a que conocen en detalle las tareas que realizan y los riesgos asociados. Además, su colaboración fortalece la cultura de seguridad y promueve el compromiso colectivo con la prevención.

        h2.mb-0(data-aos="fade-left") Evaluación del nivel de riesgo
    
    .bg-full-width.bg-color-11
      .p-4.p-md-5
        .row.mb-5
          .col-lg-4.mb-3.mb-lg-0
            figure
              img(src="@/assets/curso/tema3/7.png", data-aos="zoom-in")
          .col-lg-8
            p(data-aos="fade-left") Una vez identificados los peligros, se procede a su evaluación, determinando el nivel de riesgo, mediante el análisis de dos variables:
        
            .bg-color-3.p-4.mb-5(data-aos="fade-left")
              ul.lista-ul--color.mb-0
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right
                  p.mb-0 Probabilidad de ocurrencia.
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right
                  p.mb-0 Severidad de las consecuencias.
            p Este análisis permite jerarquizar riesgos y asignar recursos a las áreas que requieren mayor atención. Se convierte así en una herramienta clave para la toma de decisiones operativas, el diseño de controles y la mejora continua de los sistemas de gestión.
        
        div.row.justify-content-center.align-items-stretch
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema3/8.svg" alt="" style="width: 90px")
              h5.text-center Matriz de riesgos
              p.mb-0.text-center Método cualitativo/semi-cuantitativo que cruza probabilidad y severidad para determinar el nivel de riesgo.
        
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema3/9.svg" alt="" style="width: 90px")
              h5.text-center Árbol de fallos (FTA)
              p.mb-0.text-center Representación gráfica de las combinaciones de fallos que pueden generar un evento crítico.
        
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema3/10.svg" alt="" style="width: 90px")
              h5.text-center Análisis de modos y efectos de falla (AMEF)
              p.mb-0.text-center Identificación sistemática de fallos potenciales en componentes/procesos y sus consecuencias.
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema3/11.svg" alt="" style="width: 90px")
              h5.text-center Análisis Preliminar de Riesgos (APR)
              p.mb-0.text-center Herramienta proactiva aplicada en fases tempranas para anticipar riesgos antes de iniciar la operación.
    
    .bg-full-width.bg-color-4.mb-5
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema3/12.svg", style="max-width: 90px").mx-auto
          .col-lg.text-white
            p.mb-0 La correcta evaluación facilita la priorización de acciones de control, optimizando recursos y fortaleciendo la protección del personal e instalaciones.
    
    h2(data-aos="fade-left") Proceso dinámico y continuo
    p.mb-5 La evaluación de riesgos no debe entenderse como una actividad puntual. Es un proceso continuo y dinámico, que se ajusta en función de:

    .row.justify-content-center.align-items-stretch.mb-4
      .col-lg-3.mb-3.mb-lg-0
        .bg-color-6.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema3/13.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-2 01
              p.mb-0 Cambios en procesos.

      .col-lg-3.mb-3.mb-lg-0
        .bg-color-6.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema3/14.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-2 02
              p.mb-0 Introducción de nuevas tecnologías.

      .col-lg-3.mb-3.mb-lg-0
        .bg-color-6.p-2(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema3/15.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-2 03
              p.mb-0 Retroalimentación del sistema de gestión.
      .col-lg-3.mb-3.mb-lg-0
        .bg-color-6.p-3(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema3/16.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-2 04
              p.mb-0 Resultados de investigaciones de incidentes.
    
    p.mb-5 Este enfoque refuerza la cultura de mejora continua y asegura que las condiciones laborales se mantengan dentro de niveles aceptables de seguridad a lo largo del tiempo.

    h2(data-aos="fade-left") Matriz de Identificación de peligros, valoración de riesgos y determinación de controles (GTC 45)
    p.mb-5 Una referencia esencial en este proceso es la Guía Técnica Colombiana GTC 45, que establece un enfoque estructurado para la evaluación cualitativa y cuantitativa del riesgo. Esta guía promueve una gestión proactiva e inclusiva, independientemente del tamaño o sector de la organización.

    .bg-full-width.bg-color-3.mb-5
      .px-4.px-md-5
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-7(data-aos="fade-left").mb-3.mb-lg-0
                p Propósitos claves de la GTC 45:
                ul.lista-ul--color
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Identificar peligros laborales y evaluar riesgos.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Determinar medidas de control adecuadas.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Apoyar la toma de decisiones en selección de equipos, procesos y métodos de trabajo. 
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Comprobar la eficacia de los controles existentes.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Establecer prioridades en acciones correctivas.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Demostrar cumplimiento y gestión efectiva ante partes interesadas.
                p La participación activa de todos los actores del entorno laboral (empleadores, trabajadores y profesionales en seguridad) es fundamental para aplicar con éxito esta metodología.
              .col-lg-5(data-aos="zoom-in")
                img.img-fluid(src='@/assets/curso/tema3/17.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    .bg-full-width.bg-color-11.mb-5
      .px-4.px-md-5.py-4
        h2(data-aos="fade-left") Aplicación de la evaluación, según la GTC 45
        p.mb-5 La GTC 45 establece que la evaluación de riesgos debe realizarse en situaciones claves, como:

        div.row.justify-content-center.align-items-stretch
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema3/18.svg" alt="" style="width: 90px")
              h5.text-center Primero
              p.mb-0.text-center Cuando existan dudas sobre la efectividad de los controles existentes.
        
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema3/18.svg" alt="" style="width: 90px")
              h5.text-center Segundo
              p.mb-0.text-center Al buscar mejoras continuas en el sistema de gestión.
        
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema3/18.svg" alt="" style="width: 90px")
              h5.text-center Tercero
              p.mb-0.text-center Antes de realizar cambios significativos en procesos, procedimientos o infraestructura.
    
    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema3/19.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        .bg-color-9.p-4.mb-5(data-aos="fade-left")
          p.mb-0 Este marco metodológico es adaptable a distintos sectores y se alinea con una visión moderna de la gestión de la seguridad, orientada a la sostenibilidad organizacional, el bienestar integral de los trabajadores y la continuidad operativa.
        p(data-aos="fade-left") La evaluación de riesgos, tanto cualitativa como cuantitativa, constituye un pilar esencial en la gestión de la seguridad y salud ocupacional, así como en la protección ambiental y operativa. Aplicada de forma rigurosa y con enfoque participativo, permite identificar, priorizar y controlar riesgos de manera efectiva, fortaleciendo una cultura preventiva sólida, alineada con la normativa vigente y los valores éticos de la organización.
    
    .bg-full-width.bg-color-1.mb-0
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-7.order-2
            h2.mb-4(data-aos="flip-up") Consideraciones claves para desarrollar un proceso efectivo de identificación de peligros y valoración de riesgos
            p.mb-4(data-aos="fade-right") Se invita a leer el documento Consideraciones claves para desarrollar un proceso efectivo de identificación de peligros y valoración de riesgos, donde se aborda de manera detallada cómo implementar eficazmente un proceso de identificación y evaluación de riesgos en el ámbito de la seguridad y salud en el trabajo.
    
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_1.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Consideraciones claves para desarrollar un proceso efectivo de identificación de peligros y valoración de riesgos.
    
          .col-lg-5.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema3/20.png', alt='')


    .bg-full-width.border-top.actividad.bg-color-actividad
      .p-4.p-md-5
        #Actividad                
          <Actividad :cuestionario="cuestionario"/>

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.ergoibv.com/es/posts/evaluacion-riesgos-laborales-ejemplos/ " target="_blank" rel="noopener noreferrer") Ergo/IBV. (s.f.). Evaluación de riesgos laborales, ejemplos y métodos y herramientas. Ergo/IBV. 
            
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://safetya.co/gtc-45-y-el-nivel-de-probabilidad/ " target="_blank" rel="noopener noreferrer") SafetYA. (2019). GTC 45 y el nivel de probabilidad en la evaluación de riesgos. SafetYA. 



 

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=KdbIvWxGj8M " target="_blank" rel="noopener noreferrer") Centro para la Excelencia en el Aprendizaje. (2017). Matriz IPEVRIC [video]. YouTube. 



          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema3',
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>

<script>
import Actividad from '@/components/actividad/Actividad.vue'
export default {
  name: 'Tema6',
  components: {
    Actividad,
  },
  data() {
    return {
      cuestionario: {
        tema: 'Gestión de la higiene y la seguridad industrial',
        titulo: 'Ponte a prueba',
        introduccion:
          'Demuestra lo que aprendiste en esta unidad y pon a prueba tus conocimientos.',
        barajarPreguntas: true,
        preguntas: [
          {
            id: 1,
            texto: '¿Cuál es el objetivo principal de la higiene industrial?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Mejorar la productividad en las empresas.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto:
                  'Controlar los riesgos ambientales que puedan afectar la salud de los trabajadores.',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Controlar los riesgos ergonómicos.',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Evaluar el desempeño en seguridad vial industrial.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 2,
            texto: '¿Qué función cumple la seguridad industrial?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Evaluar los riesgos fisicos.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Eliminar los riesgos ambientales.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'Prevenir accidentes y enfermedades laborales.',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto: 'Incrementar la competitividad empresarial.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 3,
            texto:
              '¿Cuál de los siguientes no es un factor de riesgo higiénico?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Agentes biológicos.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Agentes químicos.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'Agentes físicos',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Comportamientos inseguros.',
                esCorrecta: true,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 4,
            texto:
              '¿Qué herramienta se utiliza para evaluar los riesgos laborales?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Encuesta de clima organizacional.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto:
                  'Matriz de identificación de peligros y evaluación de riesgos.',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Programa de inspecciones.',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Programa de incentivos.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 5,
            texto:
              '¿Qué agente físico puede evaluarse en la higiene industrial?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Ruido.',
                esCorrecta: true,
              },
              {
                id: 'b',
                texto: 'Estrés laboral.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'Violencia intrafamiliar.',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Mal clima organizacional.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
        ],
        mensaje_final_aprobado:
          '¡Felicidades! Has superado la prueba con éxito.',
        mensaje_final_reprobado:
          'Te recomendamos repasar nuevamente la unidad para reforzar los conceptos clave antes de volver a intentarlo.',
      },
    }
  },
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.bg-color-actividad
  background-color: #EBF1F5
</style>
