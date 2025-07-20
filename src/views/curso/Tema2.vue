<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'2. Metodologías de identificación de peligros (checklists, inspecciones, análisis preliminar de riesgos)'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/1.png", data-aos="zoom-in")
      .col-lg-8
        p.mb-5(data-aos="fade-left") En el contexto actual de transformación industrial, automatización y globalización de los procesos productivos, la seguridad y salud en el trabajo (SST), ha adquirido una relevancia sin precedentes. Las organizaciones modernas deben responder no solo a exigencias normativas locales e internacionales, sino también a una creciente demanda social y ética por generar entornos laborales seguros, saludables y sostenibles. En este escenario, la gestión preventiva del riesgo se posiciona como una estrategia indispensable, siendo su piedra angular la identificación sistemática de los peligros existentes o potenciales en los espacios de trabajo.
    
        .bg-color-9.p-4(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema2/2.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Dicha identificación no puede entenderse como una acción aislada ni un ejercicio mecánico, sino como un proceso integral, proactivo y estructurado, orientado a reconocer todos aquellos factores físicos, químicos, biológicos, ergonómicos, psicosociales y organizacionales, que puedan afectar negativamente la integridad de las personas, los procesos o el ambiente. Este enfoque requiere una comprensión profunda de las interacciones entre el ser humano, las herramientas que emplea, los procesos que ejecuta y el entorno en el que opera, permitiendo así, anticiparse a los eventos no deseados, implementar medidas de control eficaces y construir una cultura de seguridad sostenible.
    
    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/3.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        p.mb-5(data-aos="fade-left") Las metodologías de identificación de peligros, son herramientas fundamentales en la gestión de la SST, dado que permiten detectar, evaluar y controlar los riesgos presentes en el entorno laboral. Su correcta aplicación constituye el primer paso para prevenir accidentes, enfermedades laborales y otros incidentes que puedan comprometer a los trabajadores, las instalaciones o la continuidad operativa de las organizaciones. Este proceso no se limita a la observación de los elementos físicos y mecánicos, sino que implica también la comprensión de los factores organizacionales, humanos y tecnológicos, cuyas interacciones complejas pueden generar situaciones de riesgo. La implementación eficaz de estas metodologías es clave para establecer estrategias de intervención oportunas y efectivas, y para consolidar una cultura organizacional centrada en la prevención y la mejora continua.
    
        .bg-color-8.p-4(data-aos="fade-left")
          p.mb-0 A continuación, se describen algunas de las metodologías más comunes y efectivas, incluyendo los checklists, las inspecciones, el análisis preliminar de riesgos y otras técnicas adicionales que complementan este proceso.

    h2.mb-5(data-aos="fade-left") <em>Checklists</em> (listas de verificación)

    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/4.png", data-aos="zoom-in")
      .col-lg-8
        p.mb-5(data-aos="fade-left") Las <em>checklists</em> son herramientas sencillas, efectivas y ampliamente utilizadas para la identificación, evaluación y control de peligros en entornos laborales. Se componen de un conjunto predefinido de preguntas o ítems que abordan aspectos críticos relacionados con la seguridad, la salud y la protección del personal, así como con la integridad de instalaciones, maquinaria y procesos. Su objetivo principal es facilitar una revisión sistemática, ordenada y exhaustiva, minimizando omisiones durante inspecciones y evaluaciones.
    
        .bg-color-3.p-4(data-aos="fade-left")
          p.mb-0 Una de sus ventajas más destacadas es su simplicidad y rapidez de aplicación, lo que permite a supervisores, técnicos o responsables de seguridad, realizar inspecciones, incluso en contextos complejos. Al ser estructuradas, favorecen la uniformidad en las evaluaciones, lo que permite comparaciones a lo largo del tiempo y entre diferentes áreas o equipos. Además, pueden diseñarse específicamente para cada tipo de industria, área de trabajo o actividad, incorporando requisitos normativos, buenas prácticas y lecciones aprendidas.
    
    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/5.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        .bg-color-9.p-4.mb-5(data-aos="fade-left")
          p.mb-0 Estas listas no solo detectan condiciones inseguras o incumplimientos, sino que también facilitan la planificación de acciones correctivas y preventivas. En muchos casos, incluyen campos para registrar observaciones, responsables y fechas de seguimiento, promoviendo así una gestión proactiva y continua de la seguridad. Para mantener su efectividad, deben actualizarse periódicamente para reflejar cambios en los procesos, nuevas tecnologías o modificaciones normativas.
        p(data-aos="fade-left") Por ejemplo, en una fábrica, una <em>checklist</em> puede incluir ítems como:
    
    .bg-full-width.bg-color-7.mb-5
      .px-4.px-md-5.py-4
        .row.justify-content-center.mb-5
          .col-lg-8.mb-3.mb-lg-0.order-2
            SlyderF(columnas="col-12 col-lg-6")
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/7.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 01
                p.text-center Estado de las máquinas (sin piezas sueltas o desgastadas).
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/8.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 02
                p.text-center Presencia y visibilidad de señalización de seguridad.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/9.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 03
                p.text-center Condiciones adecuadas de iluminación y ventilación.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/10.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 04
                p.text-center Uso correcto del equipo de protección personal (EPP).
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/11.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 05
                p.text-center Almacenamiento seguro de sustancias peligrosas.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/12.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 06
                p.text-center Rutas de evacuación despejadas.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/13.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 07
                p.text-center Accesibilidad a extintores y botiquines de primeros auxilios.
    
          .col-lg-4.order-1.mb-3.mb-lg-0
            figure
              img(src='@/assets/curso/tema2/6.png', alt='')
    
        .row.mb-5
          .col-lg-4.order-lg-2.mb-3.mb-lg-0
            figure
              img(src="@/assets/curso/tema2/14.png", data-aos="zoom-in")
          .col-lg-8.order-lg-1
            p.mb-5(data-aos="fade-left") El uso sistemático de estos listados garantiza que no se omitan aspectos fundamentales y que las inspecciones se realicen de forma consistente. Además, fomentan una cultura de seguridad dentro de la organización, promoviendo la participación activa del personal en la identificación de riesgos y en la promoción de buenas prácticas.
        
            .bg-color-3.p-4(data-aos="fade-left")
              p.mb-0 Finalmente, las <em>checklists</em> aportan valor al facilitar la documentación y trazabilidad de las inspecciones, lo que resulta clave en auditorías, investigaciones de incidentes y análisis de tendencias. En resumen, son una herramienta esencial para fortalecer los sistemas de gestión de seguridad y salud en el trabajo, promoviendo entornos más seguros, responsables y alineados con estándares internacionales.
    
    h2.mb-5(data-aos="fade-left") Inspecciones de seguridad

    .bg-color-10.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto.mb-3.mb-lg-0
          figure
            img(src='@/assets/curso/tema2/15.png', alt='')
        .col-lg
          .p-4
            p.mb-0(data-aos="fade-up") Las inspecciones de seguridad son procedimientos sistemáticos y planificados cuyo propósito fundamental es la identificación temprana y exhaustiva de condiciones subestándar, actos inseguros y desviaciones respecto a los estándares establecidos en materia de seguridad y salud en el trabajo. Constituyen una práctica clave dentro de la gestión preventiva, porque permiten detectar riesgos, así como implementar acciones correctivas y preventivas, para evitar accidentes, enfermedades ocupacionales y pérdidas materiales.
    
    h2(data-aos="fade-left") Tipos de inspección
    p.mb-5 Las inspecciones pueden clasificarse, según su frecuencia y objetivo. A contininuación, se resumen las características principales de cada tipo:

    .bg-full-width.bg-fondo-1.mb-5
      .p-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-8
            ImagenInfografica.color-secundario
              template(v-slot:imagen)
                figure
                  img(src='@/assets/curso/tema2/16.svg', alt='', style="max-width: 1106px;").mx-auto
    
              .bg-color-white.box-shadow.p-3(x="79%" y="39%" numero="+")
                h5 De rutina
                p Se realizan de forma periódica (diaria, semanal o mensual) en zonas críticas.
    
              .bg-color-white.box-shadow.p-3(x="16%" y="39.8%" numero="+")
                h5 Específicas
                p Enfocadas en aspectos particulares como maquinaria, instalaciones eléctricas, sistemas de ventilación o manipulación de sustancias peligrosas.
    
              .bg-color-white.box-shadow.p-3(x="79.7%" y="72.3%" numero="+")
                h5 Extraordinarias
                p Se efectúan tras incidentes, cambios en procesos, incorporación de nuevas tecnologías o aplicación de medidas correctivas, para evaluar su efectividad.
    
    h2.mb-5(data-aos="fade-left") Proceso de inspección
    
    .bg-full-width.bg-color-3.mb-5
      .p-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-7(data-aos="fade-left").mb-3.mb-lg-0
                p El proceso implica una revisión minuciosa y documentada de factores del entorno laboral, incluyendo:
                ul.lista-ul--color
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Infraestructura física</b>: pisos, techos, escaleras, barandillas, salidas de emergencia.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Equipos de protección personal (EPP)</b>: estado y disposición.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Sustancias químicas</b>: almacenamiento y rotulado.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Señalización de seguridad y sistemas contra incendios</b>.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Condiciones ambientales</b>: iluminación, ruido.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Prácticas laborales observadas in situ.</b>
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Factores psicosociales y ergonómicos</b>, especialmente en tareas repetitivas o con alta carga mental.

              .col-lg-5(data-aos="zoom-in")
                img.img-fluid(src='@/assets/curso/tema2/17.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    h2.mb-5(data-aos="fade-left") Responsables y participación

    .bg-full-width.bg-color-11
      .p-4.p-md-5
        .bg-color-10.mb-5(data-aos="fade-up")
          .row.justify-content-center.align-items-center
            .col-lg-auto.mb-3.mb-lg-0
              figure
                img(src='@/assets/curso/tema2/18.png', alt='')
            .col-lg
              .p-4
                p.mb-0(data-aos="fade-up") Las inspecciones deben ser realizadas por personal competente, como supervisores, responsables de seguridad y salud, comités paritarios, auditores internos o consultores externos. No obstante, es clave fomentar la participación activa de los trabajadores, quienes aportan un conocimiento profundo de las condiciones reales de trabajo. Este enfoque participativo fortalece la cultura de seguridad y promueve la corresponsabilidad.
        
        h2(data-aos="fade-left") Herramientas y seguimiento
        p.mb-5 Para su eficacia, deben apoyarse en herramientas como:

        div.row.justify-content-center.align-items-stretch
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/19.svg" alt="" style="width: 90px")
              h5.text-center Primero
              p.mb-0.text-center Checklists (listas de verificación).
        
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/20.svg" alt="" style="width: 90px")
              h5.text-center Segundo
              p.mb-0.text-center Formatos de reporte estandarizados.
        
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/21.svg" alt="" style="width: 90px")
              h5.text-center Tercero
              p.mb-0.text-center Evidencia fotográfica.
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/22.svg" alt="" style="width: 90px")
              h5.text-center Cuarto
              p.mb-0.text-center <em>Software</em> especializado para la gestión digital de hallazgos.
    
    .bg-full-width.bg-color-4.mb-5
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema2/23.svg", style="max-width: 90px").mx-auto
          .col-lg.text-white
            p.mb-0 Además, es esencial contar con mecanismos de seguimiento que incluyan: responsables asignados, plazos definidos y verificación del cierre efectivo de cada hallazgo. La trazabilidad del proceso es clave para demostrar el cumplimiento legal y evaluar la evolución de los riesgos en el tiempo.
    
    h2(data-aos="fade-left") Enfoque normativo
    p.mb-5 Las inspecciones responden al cumplimiento de leyes, reglamentos y estándares nacionales e internacionales. En muchos países, su realización periódica es una obligación legal del empleador. Estándares como la ISO 45001 establecen la necesidad de identificar peligros y evaluar riesgos de forma proactiva, siendo las inspecciones una herramienta clave de control operativo.

    .bg-full-width.bg-color-3.mb-5
      .p-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-7(data-aos="fade-left").mb-3.mb-lg-0
                h5 Impacto y beneficios
                p Más allá del cumplimiento legal, las inspecciones permiten:
                ul.lista-ul--color
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Detectar fallas antes de que se conviertan en incidentes.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Reducir costos por accidentes, daños e indemnizaciones.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Mejorar la moral del personal. 
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Reforzar la imagen corporativa ante clientes y reguladores.
                p También alimentan el sistema de indicadores de gestión en seguridad (como la tasa de condiciones subestándar o el tiempo promedio de cierre de acciones), facilitando una toma de decisiones informada. Los hallazgos pueden integrarse en los programas de capacitación, ajustando contenidos a los riesgos reales observados.

              .col-lg-5(data-aos="zoom-in")
                img.img-fluid(src='@/assets/curso/tema2/24.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0

    h2.mb-5(data-aos="fade-left") Análisis preliminar de riesgos 

    .bg-color-1.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto.mb-3.mb-lg-0
          figure
            img(src='@/assets/curso/tema2/25.png', alt='')
        .col-lg
          .p-4
            p.mb-0(data-aos="fade-up") El Análisis Preliminar de Riesgos (APR) es una herramienta clave en la gestión de la seguridad industrial y la protección del medio ambiente. Se aplica en las fases iniciales de un proyecto o proceso, antes de que comience la operación, con el objetivo de detectar y evaluar peligros potenciales desde etapas tempranas. Esto permite incorporar medidas preventivas desde el diseño, reduciendo riesgos y costos asociados a modificaciones tardías o accidentes.
    
    h2(data-aos="fade-left") Objetivos del APR
    p.mb-5 El APR tiene como finalidad principal anticiparse a los riesgos. Entre sus objetivos se destacan:

    .bg-full-width.bg-color-7.mb-5
      .px-4.px-md-5.py-4
        .row.justify-content-center.mb-5
          .col-lg-8.mb-3.mb-lg-0
            SlyderF(columnas="col-12 col-lg-6")
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/26.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Identificación temprana de peligros
                p.text-center Detectar posibles causas de incidentes en la fase de diseño o planificación.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/27.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Evaluación de riesgos
                p.text-center Analizar la probabilidad y consecuencias de los peligros identificados.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/28.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Implementación de medidas preventivas
                p.text-center Introducir cambios estructurales o de procedimiento que reduzcan o eliminen los riesgos.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/29.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Optimización del diseño
                p.text-center Mejorar la seguridad y eficiencia del proceso desde su concepción. 
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/30.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Cumplimiento normativo
                p.text-center Asegurar que el proyecto cumpla con las regulaciones de seguridad aplicables.
    
          .col-lg-4
            figure
              img(src='@/assets/curso/tema2/26.png', alt='')
        
        h2(data-aos="fade-left") Fundamentación teórica
        p.mb-5 El APR se fundamenta en principios de gestión de riesgos y en una filosofía de seguridad proactiva, promoviendo una cultura de prevención más que de reacción. Se alinea con los estándares internacionales ISO 45001 y ISO 31000, integrando conceptos como:

        .row.justify-content-center.align-items-stretch.mb-4
          .col-lg-4.mb-3.mb-lg-0
            .bg-color-6.p-4(data-aos="fade-left").h-100
              .row.align-items-center
                .col-lg-auto
                  img(src="@/assets/curso/tema2/31.svg", style="max-width: 90px").mx-auto
                .col-lg
                  h5.mb-2 01
                  p.mb-0 Identificación de peligros

          .col-lg-4.mb-3.mb-lg-0
            .bg-color-6.p-4(data-aos="fade-left").h-100
              .row.align-items-center
                .col-lg-auto
                  img(src="@/assets/curso/tema2/32.svg", style="max-width: 90px").mx-auto
                .col-lg
                  h5.mb-2 02
                  p.mb-0 Evaluación de riesgos

          .col-lg-4.mb-3.mb-lg-0
            .bg-color-6.p-4(data-aos="fade-left").h-100
              .row.align-items-center
                .col-lg-auto
                  img(src="@/assets/curso/tema2/33.svg", style="max-width: 90px").mx-auto
                .col-lg
                  h5.mb-2 03
                  p.mb-0 Control de riesgos

    .bg-full-width.bg-color-11.mb-5
      .px-4.px-md-5.py-4
        h2(data-aos="fade-left") Características claves del APR
        p.mb-5 Estas características definen el enfoque y efectividad del análisis:

        div.row.justify-content-center.align-items-stretch
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/34.svg" alt="" style="width: 90px")
              h5.text-center Proactividad
              p.mb-0.text-center Se realiza antes de que ocurran incidentes.
        
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/35.svg" alt="" style="width: 90px")
              h5.text-center Participación multidisciplinaria
              p.mb-0.text-center Involucra técnicos, operarios, especialistas en seguridad y medio ambiente.
        
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/36.svg" alt="" style="width: 90px")
              h5.text-center Enfoque holístico
              p.mb-0.text-center Considera factores técnicos, humanos, organizativos y ambientales.
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/37.svg" alt="" style="width: 90px")
              h5.text-center Documentación
              p.mb-0.text-center Genera registros que facilitan seguimiento y mejora continua.
    
    h2(data-aos="fade-left") Fases del análisis preliminar de riesgos
    p.mb-5 El APR se desarrolla en etapas secuenciales que aseguran su efectividad:

    .row.align-items-center.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/38.png", alt="", data-aos="zoom-in").mb-4.mb-lg-0
      .col-lg-8.order-lg-1
        p(data-aos="fade-left") 
        
        LineaTiempoD.color-primario.large(data-aos="fade-left")
          p(numero="1" titulo="Preparación") Se define el alcance del análisis, se conforma un equipo multidisciplinario y se recopila información preliminar (diagramas, planos, procedimientos, entre otros).
          p(numero="2" titulo="Identificación de peligros") Se examinan procesos, materiales y condiciones operativas y ambientales mediante técnicas como <em>brainstorming</em>, diagramas de flujo, inspecciones y análisis previos.
          p(numero="3" titulo="Evaluación de riesgos") Se estima la probabilidad de ocurrencia y la severidad de las consecuencias, utilizando matrices de riesgo o métodos cualitativos y semicuantitativos.
          p(numero="4" titulo="Medidas preventivas y correctivas") Se proponen acciones como rediseños, implementación de sistemas de control, alarmas, barreras físicas, mejoras procedimentales y programas de capacitación. 
          p(numero="5" titulo="Documentación y seguimiento") Se registran los hallazgos y decisiones, se asignan responsables para cada acción y se realizan revisiones periódicas del análisis.
    
    h2(data-aos="fade-left") Participación del equipo
    p.mb-5 El éxito del APR depende de la colaboración entre diversos perfiles. Se recomienda incluir:

    .bg-full-width.bg-color-7
      .px-4.px-md-5
        .row.justify-content-center.mb-5
          .col-lg-8.mb-3.mb-lg-0.order-lg-2
            SlyderF(columnas="col-12 col-lg-6")
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/39-1.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 01
                p.text-center Expertos técnicos (ingenieros, técnicos de procesos).
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/39-2.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 02
                p.text-center Personal operativo (operadores y supervisores).
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/39-3.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 03
                p.text-center Especialistas en seguridad y salud laboral.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/39-4.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 04
                p.text-center Representantes de los trabajadores.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/39-5.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 05
                p.text-center Ambientalistas, en caso de impactos ambientales potenciales.
    
          .col-lg-4.order-lg-1
            figure
              img(src='@/assets/curso/tema2/39.png', alt='')
        .bg-full-width.bg-color-4
          .px-4.px-md-5.py-4
            .row.align-items-center
              .col-lg-auto
                img(src="@/assets/curso/tema2/40.svg", style="max-width: 90px").mx-auto
              .col-lg.text-white
                p.mb-0 Aunque es ideal contar con una visión amplia, el APR puede realizarse con un equipo más reducido, adaptado a la magnitud del proyecto.
    
    .bg-full-width.bg-color-3.mb-5
      .p-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center.mb-5
              .col-lg-7(data-aos="fade-left").mb-3.mb-lg-0
                h2(data-aos="fade-left") Beneficios del APR
                p.mb-5 Implementar el APR trae ventajas significativas:
                ul.lista-ul--color
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Reducción de incidentes y accidentes.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Ahorro en costos por evitar correcciones tardías.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Mejoras en el diseño y operación.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Cumplimiento regulatorio y de estándares internacionales.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Fomento de la cultura preventiva.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Mejora continua, integrando lecciones aprendidas en futuras etapas.


              .col-lg-5(data-aos="zoom-in")
                img.img-fluid(src='@/assets/curso/tema2/41.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
            
            h2.mb-5(data-aos="fade-left") Consideraciones para una implementación efectiva
            .row.justify-content-center.align-items-center.mb-5
              .col-lg-7(data-aos="fade-left").mb-3.mb-lg-0.order-lg-2
                p.mb-5 Para asegurar la calidad del análisis, se recomienda:
                ul.lista-ul--color
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Compromiso de la alta dirección</b>, con apoyo y recursos adecuados.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Capacitación del equipo</b> en metodologías de análisis de riesgos. 
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Actualización continua</b> ante cambios en el proceso o normativas.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Integración con otros sistemas de gestión</b> (calidad, medio ambiente, SST).
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Comunicación efectiva</b> de hallazgos y decisiones a todos los involucrados.


              .col-lg-5(data-aos="zoom-in").order-lg-1
                img.img-fluid(src='@/assets/curso/tema2/42.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
            
            .row.justify-content-center.align-items-center
              .col-lg-7(data-aos="fade-left").mb-3.mb-lg-0
                h2(data-aos="fade-left") Limitaciones y desafíos del APR
                p Como toda herramienta, el APR enfrenta ciertas limitaciones:
                ul.lista-ul--color
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Subjetividad en evaluaciones cualitativas.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Riesgo de omitir peligros en etapas tempranas. 
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Resistencia al cambio por parte del personal.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Necesidad de tiempo y recursos para su adecuada aplicación.


              .col-lg-5(data-aos="zoom-in")
                img.img-fluid(src='@/assets/curso/tema2/43.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    h2(data-aos="fade-left") Árbol de Fallos (FTA)
    p.mb-5 El Árbol de Fallos (FTA), es una técnica sistemática y gráfica utilizada para analizar las causas que pueden conducir a un evento no deseado, conocido como evento raíz o evento principal. Este método permite visualizar las combinaciones de errores o fallos que pueden desencadenar fallas críticas en sistemas complejos, ayudando al diseño de medidas preventivas y correctivas. Los componentes principales del árbol de fallos:

    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema2/44.png")
            .col-lg-7
              h5 Evento principal (<em>Top Event</em>)
              p Es la falla o accidente que se desea evitar o comprender. Ejemplos: caída de una estructura, fallo en sistema de control, fuga de sustancias peligrosas.
    
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema2/45.png")
            .col-lg-7
              h5 Eventos intermedios
              p Contribuyen directamente al evento principal. Se representan como nodos intermedios en el árbol.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema2/46.png")
            .col-lg-7
              h5 Eventos básicos (primarios) 
              p Son las causas raíz más fundamentales que pueden originar los eventos intermedios o directamente el evento principal. No se descomponen más.
    
    h2(data-aos="fade-left") Construcción del Árbol de Fallos
    p.mb-5 La creación del Árbol de Fallos, sigue una secuencia estructurada que asegura la trazabilidad y comprensión del sistema analizado:

    .row.align-items-center.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/47.png", alt="", data-aos="zoom-in").mb-4.mb-lg-0
      .col-lg-8.order-lg-1
        p(data-aos="fade-left") 
        
        LineaTiempoD.color-primario.large(data-aos="fade-left")
          p(numero="1" titulo="Definición del evento no deseado") Se determina con precisión cuál es el evento que se desea evitar o comprender, sirviendo como punto de partida del análisis.
          p(numero="2" titulo="Identificación de causas potenciales") Se recopilan todas las posibles causas mediante revisión de experiencias anteriores, análisis de fallos, registros históricos, entrevistas y otras fuentes de información.
          p(numero="3" titulo="Descomposición en niveles") Las causas se organizan jerárquicamente: desde eventos básicos, pasando por eventos intermedios, hasta llegar al evento principal.
          p(numero="4" titulo="Representación gráfica") Se construye el árbol con el evento principal en la parte superior y las causas distribuidas en ramas descendentes, conectadas con puertas lógicas (AND, OR, entre otras).
    
    .bg-full-width.bg-color-11
      .p-4.p-md-5
        h2(data-aos="fade-left") Análisis y utilidad del Árbol de Fallos
        p.mb-5 El Árbol de Fallos permite:

        div.row.justify-content-center.align-items-stretch
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/48.svg" alt="" style="width: 90px")
              h5.text-center Identificación de causas principales.
              p.mb-0.text-center Determina qué combinaciones específicas de fallos, pueden generar el evento no deseado.
        
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/49.svg" alt="" style="width: 90px")
              h5.text-center Evaluación de la probabilidad del evento principal.
              p.mb-0.text-center Usando datos de probabilidad de los eventos básicos, se puede calcular la probabilidad global del evento raíz, lo que apoya la evaluación cuantitativa del riesgo.
        
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/50.svg" alt="" style="width: 90px")
              h5.text-center Detección de puntos débiles.
              p.mb-0.text-center Identifica procesos o componentes críticos, que requieren atención especial o mejoras.
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/51.svg" alt="" style="width: 90px")
              h5.text-center Planificación de acciones preventivas.
              p.mb-0.text-center Facilita el diseño de controles, modificaciones o refuerzos, para eliminar o mitigar las causas raíz detectadas.
    
    h2.mb-5(data-aos="fade-left") Ventajas del método FTA

    .bg-full-width.bg-color-3.mb-5
      .px-4.px-md-5
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-7(data-aos="fade-left").mb-3.mb-lg-0.order-lg-2
                p El uso del Árbol de Fallos ofrece múltiples beneficios:
                ul.lista-ul--color
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Visualización clara</b> de relaciones causa-efecto en sistemas complejos.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Análisis estructurado y detallado</b> que permite detectar fallos que podrían pasar desapercibidos en otros métodos.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Aplicabilidad tanto cualitativa como cuantitativa</b>, adaptable a diferentes tipos de sistemas.
                  li.mb-3.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Versatilidad</b> para analizar desde fallos técnicos hasta errores humanos o de gestión.

              .col-lg-5(data-aos="zoom-in").order-lg-1
                img.img-fluid(src='@/assets/curso/tema2/52.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    h2.mb-5(data-aos="fade-left") Consideraciones finales

    .bg-color-10.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto.order-2
          figure
            img(src='@/assets/curso/tema2/53.png', alt='')
        .col-lg.order-1.mb-3.mb-lg-0
          .p-4
            p.mb-0(data-aos="fade-up") Si bien existen diversas metodologías de identificación de peligros a nivel internacional, el FTA es una de las más comunes y efectivas, especialmente en entornos donde se requiere una comprensión profunda de fallos complejos. En el anexo de esta guía, encontrará formatos modelo que servirán como apoyo para la aplicación práctica de esta metodología.




    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://inchecksas.com/herramienta-para-la-identificacion-de-peligros-y-valoracion-de-riesgos/" target="_blank" rel="noopener noreferrer") Giraldo Arias, C. A. (2021). Herramienta para la Identificación de peligros y valoración de riesgos. In Check S.A.S.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.isotools.us/normas/riesgos-y-seguridad/iso-45001/ " target="_blank" rel="noopener noreferrer") ISOTools. (s.f.). ¿Qué es la Norma ISO 45001? 

  


            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=adNuoWxs9NI " target="_blank" rel="noopener noreferrer") CATP Consultant. (2023). IDENTIFICACIÓN DE PELIGROS- EVALUACIÓN y VALORACIÓN DE RIESGOS. SGSST [video]. YouTube. 



          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema2',
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
