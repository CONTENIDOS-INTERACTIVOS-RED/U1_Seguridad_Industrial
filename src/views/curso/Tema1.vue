<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'1. Conceptos fundamentales de higiene y seguridad industrial'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/1.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        p(data-aos="fade-left") La higiene y la seguridad industrial, son disciplinas fundamentales dentro del campo de la salud ocupacional. Su objetivo principal es proteger la vida, la integridad física y la salud de los trabajadores frente a los riesgos derivados de las actividades laborales. Estas disciplinas se complementan para identificar, evaluar, controlar y prevenir factores que puedan generar accidentes de trabajo o enfermedades laborales.
    
        .bg-color-3.p-4.mb-5(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema1/2.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 En los entornos industriales, donde los procesos productivos involucran maquinaria, sustancias químicas, energías y condiciones ambientales variables, la aplicación rigurosa de estas disciplinas es esencial para garantizar entornos laborales seguros y saludables.

        p A continuación se presenta una comparación entre los conceptos fundamentales de higiene industrial y seguridad industrial:
    
    .titulo-figura.mb-4
      h5 Tabla 1.
      span Comparación higiene industrial y seguridad industrial
    .tabla-a.color-acento-botones.mb-5
      table
        thead
          tr.text-center
            th.bg-color-4.text-white.text-center Higiene industrial
            th.bg-color-4.text-white.text-center Seguridad industrial
        tbody.bg-color-5
          tr
            td Se enfoca en el estudio, evaluación y control de agentes ambientales que afectan la salud del trabajador.
            td Se orienta a prevenir accidentes laborales, mediante la identificación y control de riesgos.
          tr
            td Agentes: físicos (ruido, radiaciones, temperatura), químicos (gases, polvos, vapores), biológicos (virus, bacterias, hongos).
            td Riesgos: mecánicos (golpes, atrapamientos), eléctricos, incendios, explosiones, caídas, etc.
          tr
            td Su finalidad es anticipar enfermedades profesionales.
            td Su finalidad es evitar lesiones y daños materiales.
          tr
            td Aplica metodologías como medición ambiental, observación directa, entrevistas, y evaluaciones técnicas.
            td Utiliza normas técnicas, procedimientos seguros, capacitación continua, EPP y diseño ergonómico.
          tr
            td “La metodología de aplicación [...] está basada en la identificación, medida, evaluación y control de los contaminantes presentes en el ambiente de trabajo” (Castejón Vilella, E., Guardino Solá, X. & Baraza Sánchez, X., 2014).
            td Aplica el control jerárquico de riesgos: eliminación, sustitución, controles de ingeniería, administrativos y EPP.
    
    p.mb-5 Ambas disciplinas comparten principios claves como:

    .bg-full-width.bg-color-7
      .p-4.p-md-5
        .row.justify-content-center.align-items-stretch.mb-4
          .col-lg-4.mb-3.mb-lg-0
            .bg-color-6.p-4(data-aos="fade-left").h-100
              .row.align-items-center
                .col-lg-auto
                  img(src="@/assets/curso/tema1/3.svg", style="max-width: 90px").mx-auto
                .col-lg
                  h5.mb-2 01
                  p.mb-0 Prevención y control jerárquico de riesgos.

          .col-lg-4.mb-3.mb-lg-0
            .bg-color-6.p-4(data-aos="fade-left").h-100
              .row.align-items-center
                .col-lg-auto
                  img(src="@/assets/curso/tema1/4.svg", style="max-width: 90px").mx-auto
                .col-lg
                  h5.mb-2 02
                  p.mb-0 Mejora continua de condiciones laborales.

          .col-lg-4.mb-3.mb-lg-0
            .bg-color-6.p-4(data-aos="fade-left").h-100
              .row.align-items-center
                .col-lg-auto
                  img(src="@/assets/curso/tema1/5.svg", style="max-width: 90px").mx-auto
                .col-lg
                  h5.mb-2 03
                  p.mb-0 Participación activa de toda la organización.

        h2(data-aos="fade-left") Marco legal y gestión en Colombia
        
        .row.mb-5
          .col-lg-4.mb-3.mb-lg-0
            figure
              img(src="@/assets/curso/tema1/6.png", data-aos="zoom-in")
          .col-lg-8
            p.mb-4(data-aos="fade-left") La legislación laboral en muchos países exige la implementación de medidas de higiene y seguridad. En Colombia, destacan:
        
            .bg-color-8.p-4.mb-4(data-aos="fade-left")
              ul.lista-ul--color.mb-0
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right
                  p.mb-0 Ley 1562 del 2012.
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right
                  p.mb-0 Decreto 1072 del 2015.
            p Estas normas establecen los lineamientos del Sistema de Gestión de Seguridad y Salud en el Trabajo (SG-SST), definiendo las responsabilidades de empleadores y trabajadores.
      
    h2.mb-5(data-aos="fade-left") Elementos claves en la gestión de higiene y seguridad
    
    .bg-full-width.bg-color-3.mb-5
      .p-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-7(data-aos="fade-left").mb-3.mb-lg-0
                p Entre los componentes fundamentales se encuentran:
                ul.lista-ul--color
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Evaluación de riesgos y planificación de actividades preventivas.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Vigilancia epidemiológica y formación continua del personal.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Inspección de condiciones laborales e investigación de accidentes e incidentes.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Promoción de una cultura de seguridad, mediante sensibilización, comunicación efectiva y liderazgo.
                p Un entorno laboral que prioriza la seguridad y el bienestar, incrementa la productividad, reduce el ausentismo, minimiza contingencias legales y mejora el clima organizacional.
              .col-lg-5(data-aos="zoom-in")
                img.img-fluid(src='@/assets/curso/tema1/7.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    h2.mb-5(data-aos="fade-left") Enfoque integral y normas internacionales

    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/8.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        p.mb-5(data-aos="fade-left") La integración con disciplinas como la ergonomía, la psicología organizacional y la gestión ambiental, ha dado lugar a sistemas de gestión integrados, que no solo cumplen una función normativa, sino que también impulsan la sostenibilidad organizacional y la responsabilidad social empresarial.
    
        .bg-color-1.p-4(data-aos="fade-left")
          p.mb-0 Uno de los marcos más reconocidos es la ISO 45001, que promueve un enfoque sistemático para prevenir lesiones y enfermedades laborales.
    
    h2.mb-5(data-aos="fade-left") Condiciones para una aplicación efectiva
    
    .bg-full-width.bg-color-3.mb-5
      .p-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-7(data-aos="fade-left").order-lg-2.mb-3.mb-lg-0
                p Para aplicar correctamente los conceptos de higiene y seguridad industrial, es necesario:
                ul.lista-ul--color
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Contar con personal capacitado y recursos técnicos adecuados.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Implementar un enfoque interdisciplinario.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Realizar vigilancia continua de ambientes de trabajo.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Analizar condiciones peligrosas y actualizar protocolos ante nuevas tecnologías o sustancias.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Tratar la investigación de incidentes como una oportunidad de aprendizaje, para prevenir recurrencias.

              .col-lg-5(data-aos="zoom-in").order-lg-1
                img.img-fluid(src='@/assets/curso/tema1/9.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0

    h2.mb-5(data-aos="fade-left") Conceptos básicos de higiene y seguridad industrial

    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/10.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        .bg-color-9.p-4.mb-5(data-aos="fade-left")
          p.mb-0 Los conceptos fundamentales de higiene y seguridad industrial, constituyen la base de cualquier estrategia efectiva de prevención de riesgos laborales. Su correcta implementación debe integrarse en la planificación estratégica de las organizaciones, con el respaldo de la alta dirección y la participación activa de los trabajadores.
        p(data-aos="fade-left") Un entorno industrial seguro no solo protege la salud y la vida de las personas, sino que también fortalece la productividad, mejora la eficiencia y refuerza la reputación de la empresa, en un mercado competitivo. Además, la inversión en estos aspectos refleja un compromiso ético y social de las organizaciones, promoviendo un desarrollo sostenible y responsable. Los principales conceptos relacionados son: 
    
    .bg-full-width.bg-fondo-slider
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema1/11.png")
            .col-lg-7
              h5 Actos inseguros
              p Comportamientos humanos que incrementan la posibilidad de un accidente (como operar maquinaria sin autorización).
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema1/12.png")
            .col-lg-7
              h5 Condiciones inseguras
              p Circunstancias físicas en el entorno de trabajo, que pueden favorecer la ocurrencia de accidentes (ejemplo, pisos resbalosos, cables sueltos).
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema1/13.png")
            .col-lg-7
              h5 Agente de riesgo
              p Todo factor presente en el ambiente laboral que puede dañar la salud o integridad del trabajador. Pueden ser físicos, químicos, biológicos, ergonómicos o psicosociales.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema1/14.png")
            .col-lg-7
              h5 Peligro
              p Fuente, situación o acto con potencial de causar daño en términos de lesiones, enfermedades o daños materiales o ambientales.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema1/15.png")
            .col-lg-7
              h5 Riesgo
              p Probabilidad de que un peligro cause un daño, considerando la gravedad de sus consecuencias y la frecuencia de exposición.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema1/16.png")
            .col-lg-7
              h5 Evaluación de riesgo
              p Proceso sistemático para estimar el nivel de riesgo y decidir acciones preventivas o correctivas.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema1/17.png")
            .col-lg-7
              h5 Medidas de control
              p Acciones para eliminar, sustituir o reducir riesgos: controles de ingeniería, administrativos o uso de EPP.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema1/18.png")
            .col-lg-7
              h5 Elementos de protección personal (EPP)
              p Dispositivos que protegen al trabajador frente a riesgos específicos cuando no es posible eliminar el peligro. Ejemplo, guantes, gafas, cascos.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema1/19.png")
            .col-lg-7
              h5 Riesgo higiénico 
              p Riesgo derivado de la exposición a agentes físicos, químicos o biológicos presentes en el ambiente de trabajo. 
              p “El riesgo higiénico es la probabilidad de que un trabajador sufra un daño con ocasión o a consecuencia de su trabajo, en particular por la exposición ambiental”. (Castejón Vilella, E., Guardino Solá, X. y Baraza Sánchez, X., 2014).
    
    .bg-full-width.bg-color-4.mb-0
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema1/20.svg", style="max-width: 90px").mx-auto
          .col-lg.text-white
            p.mb-0 Estos conceptos son esenciales para introducirnos en el estudio técnico y práctico de la higiene y seguridad industrial. Conocerlos permite una mejor gestión del riesgo, fomenta la cultura preventiva y asegura el cumplimiento de las normas legales y éticas, en el entorno laboral.

    
        

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.minsalud.gov.co/sites/rid/Lists/BibliotecaDigital/RIDE/DE/DIJ/Ley-1562-de-2012.pdf " target="_blank" rel="noopener noreferrer") Ley 1562 de 2012. Por la cual se modifica el sistema de riesgos laborales y se dictan otras disposiciones en materia de salud ocupacional. 11 de julio de 2012. 
            
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://safetyculture.com/es/temas/higiene-y-seguridad-industrial/ " target="_blank" rel="noopener noreferrer") SafetyCulture. (2025). Comprender la seguridad e higiene industrial. SafetyCulture.  


            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=vIBbHZtvXps " target="_blank" rel="noopener noreferrer") Laura Marcela López Posada. (2020). Higiene y seguridad en el trabajo [video]. YouTube. 



          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({}),

  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
