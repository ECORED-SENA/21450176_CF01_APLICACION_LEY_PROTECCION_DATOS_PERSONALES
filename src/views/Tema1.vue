<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido
        .titulo-principal__numero
          span 1
        h1 Fundamentos de la protección de datos personales
      p(data-aos="fade-right") A continuación, se presenta un video sobre la protección de datos personales, en el que se explican sus principios fundamentales, su importancia para la garantía de los derechos de las personas y su papel en la gestión responsable de la información dentro de las organizaciones.
      .row.justify-content-center.align-items-center           
        .col-lg-12
          figure
            .video
              iframe(width="560" height="315" src="https://www.youtube.com/embed/YZ0DZ1iQjak?si=BAeX6F7kMST8B1td" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      Separador
      //- Inicio Tema1.1
      .row
        #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
          h2 1.1 Concepto de protección de datos personales
      p(data-aos="fade-left") La protección de datos personales comprende el conjunto de principios, normas, procedimientos y medidas destinados a garantizar que la información de las personas sea tratada de manera adecuada y conforme con la normativa vigente. Su aplicación orienta las actividades de recolección, almacenamiento, uso, circulación, conservación y eliminación de los datos dentro de una organización.
      .row.align-items-center.mb-4
        .col-12.col-lg-5.order-1.order-lg-2.mb-4.mb-lg-0(data-aos="fade-left")
          figure.mb-0
            img.mx-auto(src="@/assets/curso/temas/t1/img1.png", data-aos="zoom-in", style="width: 500px; width: 100%;")
        .col-12.col-lg-7.order-2.order-lg-1(data-aos="fade-right")
          p.p-3.bg-color-3.mb-3 El crecimiento de las tecnologías digitales y el intercambio constante de información han incrementado la necesidad de aplicar estos mecanismos de protección. Cada vez que una persona realiza una compra, diligencia un formulario, crea una cuenta en una plataforma digital o utiliza una aplicación móvil, genera datos que pueden ser tratados por organizaciones públicas o privadas.
          p.p-3.bg-color-4.rounded-4.mb-0 Por esta razón, la protección de datos debe aplicarse durante todo el ciclo de vida de la información, desde su recolección hasta su eliminación, con el fin de garantizar que cada operación responda a una finalidad legítima y autorizada.
      //- Título nivel 3 - Imagen
      .titulo-tercer-nivel.mb-5.mt-3(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/temas/bg/titulos.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 Información personal y privacidad
      //- Título nivel 3 - Imagen
      p(data-aos="fade-left") La información personal corresponde a cualquier dato que permita identificar o hacer identificable a una persona natural. Estos datos pueden presentarse de manera individual o combinarse con otros elementos para determinar la identidad de un individuo. Algunos ejemplos de información personal son los siguientes:
      .row.bg-fondo-1(data-aos="fade-right")
        .col-12
          .pt-3.pb-5.px-5
            //- Carrusel
            .bg-full-width
              .px-4.px-md-5.pb-md-3
                .carousel-bg
                  .row.justify-content-center.mb-5.align-items-center
                    .col-lg-8.mb-3.mb-lg-0.order-lg-2
                      SlyderF(columnas="col-xl-6 col-lg-6 col-md-6 col-12")
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t1/tarjeta01_1.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Datos de identificación
                            p.text-center Nombre, documento de identidad y firma.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t1/tarjeta01_2.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Datos de contacto
                            p.text-center Dirección, teléfono y correo electrónico.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t1/tarjeta01_3.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Datos laborales
                            p.text-center Cargo, empresa y experiencia profesional.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t1/tarjeta01_4.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Datos financieros
                            p.text-center Cuenta bancaria e historial crediticio.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t1/tarjeta01_5.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Datos biométricos
                            p.text-center Huella dactilar y reconocimiento facial.
                    .col-lg-4.order-lg-1.d-none.d-lg-block
                        figure
                          img(src='@/assets/curso/temas/t1/img2.png', style="width: 500px", data-aos="zoom-in").m-auto
              //- Fin Carrusel
            p(data-aos="fade-left") Estas categorías permiten comprender que la información personal abarca diferentes ámbitos de la vida de una persona y que todos ellos requieren un tratamiento adecuado conforme a la legislación vigente. 
            p(data-aos="fade-left") La privacidad es el derecho que tiene cada persona para decidir quién puede acceder a su información y con qué finalidad puede utilizarla. Este derecho permite que los individuos mantengan el control sobre los datos relacionados con su vida personal, familiar, laboral y económica.
      .bloque-texto-g.bg-color-5.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-left")
        .bloque-texto-g__img(
          :style="{ backgroundImage: `url(${require_src('@/assets/curso/temas/t1/img3.png')})` }")
        .bloque-texto-g__texto.p-4
          p.mb-0 <b>Ejemplo:</b><br><br>
          p Una empresa solicita a sus trabajadores información relacionada con sus datos de contacto para gestionar procesos internos de comunicación. En este caso, la organización debe garantizar que la información sea utilizada únicamente para la finalidad informada y autorizada, y que no sea divulgada a terceros sin el consentimiento del titular o sin una causa legal que lo permita.<br><br>
          p Este ejemplo permite comprender que la protección de la privacidad depende tanto del uso adecuado de la información como del cumplimiento de las obligaciones legales por parte de la organización.
      //- Título nivel 3 - Imagen
      .titulo-tercer-nivel.mb-5.mt-3(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/temas/bg/titulos.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 Importancia de la protección de datos
      //- Título nivel 3 - Imagen
      .row.justify-content-center.align-items-stretch.mb-3.g-0(data-aos="fade-right")
        .col-lg-7.bg-color-2.d-flex.flex-column.justify-content-center.p-4
          p.mb-3 La protección de datos personales resulta fundamental para fortalecer la confianza en las relaciones entre las personas y las organizaciones. Cuando una entidad administra adecuadamente la información, genera credibilidad, protege los derechos de los titulares y demuestra compromiso con el cumplimiento de la normativa. Entre los principales beneficios de una adecuada protección de datos se encuentran los siguientes:
          ul.lista-ul.color-vinotinto-custom.mb-0
            li.d-flex
              .fas.fa-check-circle.me-3
              span Protección de la privacidad de las personas.
            li.d-flex
              .fas.fa-check-circle.me-3
              span Prevención del uso indebido de la información.
            li.d-flex
              .fas.fa-check-circle.me-3
              span Fortalecimiento de la confianza institucional.
            li.d-flex
              .fas.fa-check-circle.me-3
              span Cumplimiento de las obligaciones legales.
            li.d-flex
              .fas.fa-check-circle.me-3
              span Reducción de riesgos operativos y reputacionales.
            li.d-flex
              .fas.fa-check-circle.me-3
              span Mejoramiento de la gestión de la información.
        .col-lg-5.d-flex
          figure.mb-0.w-100
            img.h-100.w-100(src='@/assets/curso/temas/t1/img4.png', alt='', style="object-fit: cover;")
      p(data-aos="fade-left") Estos beneficios contribuyen al fortalecimiento de la gestión organizacional, favorecen la continuidad de los procesos y disminuyen la probabilidad de incidentes relacionados con el tratamiento de los datos personales.
      .row.align-items-center.mb-4
        .col-12.col-lg-5.mb-4.mb-lg-0(data-aos="fade-right")
          figure.mb-0
            img.mx-auto(src="@/assets/curso/temas/t1/img5.png", data-aos="zoom-in", style="width: 100%; max-width: 500px;")
        .col-12.col-lg-7(data-aos="fade-left")
          .bg-color-6.p-3.mb-3
            p.fw-bold Ejemplo:
            p.mb-0 Una institución educativa implementa controles de acceso a las bases de datos de estudiantes para garantizar que únicamente el personal autorizado pueda consultar o modificar la información académica. Esta medida protege la privacidad de los estudiantes, fortalece la seguridad de la información y reduce los riesgos asociados con accesos no autorizados o modificaciones indebidas.
          .bg-color-7.p-3
            p.mb-0 Este caso evidencia que la implementación de controles de seguridad constituye una práctica esencial para garantizar la protección de los datos personales y fortalecer la confianza en la gestión institucional.
      //- Título nivel 3 - Imagen
      .titulo-tercer-nivel.mb-5.mt-3(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/temas/bg/titulos.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 Riesgos asociados al manejo inadecuado de datos
      //- Título nivel 3 - Imagen
      p(data-aos="fade-left") El tratamiento inadecuado de los datos personales puede generar consecuencias negativas tanto para las personas como para las organizaciones. La pérdida, alteración, divulgación, acceso no autorizado o uso indebido de la información puede afectar derechos fundamentales, interrumpir procesos institucionales y ocasionar sanciones legales. Los riesgos más frecuentes y sus posibles consecuencias se relacionan a continuación:
      .row.bg-fondo-1(data-aos="fade-right")
        .col-12
          .pt-3.pb-5.px-5
            //- Carrusel
            .bg-full-width.mt-5
              .px-4.px-md-5.pb-md-3
                .carousel-bg
                  .row.justify-content-center.mb-5.align-items-center
                    .col-lg-8.mb-3.mb-lg-0.order-lg-2
                      SlyderF(columnas="col-xl-6 col-lg-6")
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t1/tarjeta02_1.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Acceso no autorizado
                            p.text-center Exposición de información confidencial.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t1/tarjeta02_2.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Robo de identidad
                            p.text-center Suplantación de personas.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t1/tarjeta02_3.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Pérdida de información
                            p.text-center Interrupción de procesos.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t1/tarjeta02_4.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Uso indebido de datos
                            p.text-center Vulneración de derechos.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t1/tarjeta02_5.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Filtración de información
                            p.text-center Afectación reputacional.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t1/tarjeta02_6.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Incumplimiento normativo
                            p.text-center Multas y sanciones.
                    .col-lg-4.order-lg-1.d-none.d-lg-block
                        figure
                          img(src='@/assets/curso/temas/t1/img6.png', style="width: 500px", data-aos="zoom-in").m-auto
        //- Fin Carrusel
      .row.justify-content-center.align-items-stretch
        .col-12.col-md-6.col-lg-5.mb-4.mb-lg-0(data-aos="fade-right")
          .bg-color-9.p-4.rounded-4.h-100.d-flex.align-items-center
            p.mb-0 La materialización de estos riesgos puede afectar la confidencialidad, la integridad y la disponibilidad de la información. Por esta razón, las organizaciones deben implementar medidas administrativas, técnicas y organizacionales que permitan identificar, evaluar, controlar y mitigar los riesgos durante todo el ciclo de vida de los datos personales.
        .col-12.col-md-6.col-lg-3.mb-4.mb-lg-0(data-aos="zoom-in")
          .h-100.d-flex
            img.rounded-3(src="@/assets/curso/temas/t1/img7.png", alt="", style="width: 100%; height: 100%; object-fit: cover;")
        .col-12.col-md-12.col-lg-4(data-aos="fade-left")
          .h-100.d-flex.flex-column.justify-content-end.ps-lg-4
            .mb-3.d-flex.justify-content-start
              img(src="@/assets/curso/temas/bg/icono.svg", alt="", style="width: 90px; height: 90px; object-fit: contain;")
            p.mb-0 Una adecuada gestión del riesgo fortalece el cumplimiento normativo, protege los derechos de los titulares y contribuye a preservar la continuidad de las operaciones institucionales.
      Separador
      //- Inicio Tema1.2
      .row
        #t_1_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
          h2 1.2 Evolución de la protección de datos 
      .row.mb-3.justify-content-center.align-items-center
          .col-12.col-sm-9.col-lg-5.order-1.order-lg-1.mb-4.mb-lg-0(data-aos="fade-left")
            figure.mb-0.text-center
              img(src='@/assets/curso/temas/t1/img8.png' style="width: 500px").m-auto
          .col-12.col-lg-7.order-2.order-lg-2.bg-color-2.p-4(data-aos="fade-right")
            p La protección de datos personales ha evolucionado como respuesta al crecimiento de las tecnologías de la información y a la necesidad de regular el uso de la información personal. A medida que aumentó la capacidad para recopilar, almacenar y procesar datos, surgió la necesidad de establecer normas que garantizaran la protección de los derechos de las personas y promovieran un tratamiento responsable de la información.
      p(data-aos="fade-left") Los avances tecnológicos han permitido que la información circule con rapidez entre organizaciones, plataformas y países. Esta realidad ha impulsado la creación de marcos normativos orientados a regular el tratamiento de los datos personales, fortalecer la seguridad de la información y promover el respeto por los derechos de los titulares. Los principales referentes que han marcado la evolución de la protección de datos personales se presentan a continuación:
      //- Slideshow
      .bg-full-width.bg-fondo-slider.mb-3
        .p-4.p-md-5
          SlyderA(tipo="b").bg-white.p-4.tarjeta(data-aos="fade-left")
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                 img(src='@/assets/curso/temas/t1/tarjeta03_1.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Antecedentes internacionales
                p La protección de los datos personales comenzó a consolidarse en el ámbito internacional como respuesta a la necesidad de regular el tratamiento de la información almacenada en sistemas automatizados. Instrumentos como la <b>Declaración Universal de los Derechos Humanos, el Convenio 108 del Consejo de Europa, la Directiva Europea 95/46/CE y el Reglamento General de Protección de Datos (RGPD)</b> establecieron principios y obligaciones que sirvieron de referencia para el desarrollo de las legislaciones nacionales orientadas a proteger la información personal.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t1/tarjeta03_2.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Marco normativo colombiano
                p En Colombia, la protección de datos personales tiene fundamento constitucional y legal. La Constitución Política reconoce el derecho de las personas a conocer, actualizar y rectificar la información recopilada sobre ellas en bases de datos o archivos. Posteriormente, diferentes disposiciones legales fortalecieron este derecho y establecieron obligaciones para quienes realizan el tratamiento de datos personales, promoviendo un manejo legal, transparente, seguro y responsable de la información.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t1/tarjeta03_3.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Protección de datos en entornos digitales
                p La transformación digital ha incrementado significativamente la generación, el almacenamiento y el intercambio de datos personales. Como consecuencia, han surgido riesgos como ciberataques, robo de credenciales, filtración de información, suplantación de identidad, fraudes electrónicos y uso indebido de datos personales. Para enfrentar estos desafíos, las organizaciones deben implementar controles de seguridad, políticas institucionales y mecanismos de protección que garanticen la confidencialidad, la integridad y la disponibilidad de la información durante todo su ciclo de vida.
      //- Fin Slideshow
      .bloque-texto-g.bloque-texto-g--inverso.color-acento-contenido.p-3.p-sm-4.p-md-5
        .bloque-texto-g__img(
          :style="{ backgroundImage: `url(${require_src('@/assets/curso/temas/t1/img9.png')})` }")
        .bloque-texto-g__texto.p-4
          p.mb-0 Cada uno de estos aspectos ha contribuido al fortalecimiento de la protección de datos personales, permitiendo que las organizaciones desarrollen mecanismos cada vez más efectivos para garantizar el respeto por los derechos de los titulares y el cumplimiento de las obligaciones legales.
            br
            br
            p <b>Ejemplo:</b>
            br
            br
            p Una empresa de servicios solicita autorización previa a sus clientes antes de enviar comunicaciones comerciales. Esta práctica refleja la aplicación del marco normativo sobre protección de datos personales, ya que informa la finalidad del tratamiento y obtiene el consentimiento del titular antes de utilizar su información para actividades comerciales.
      Separador
      //- Inicio Tema1.3
      .row
        #t_1_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
          h2 1.3 Importancia organizacional de la protección de datos 
      .row.align-items-center.mb-4
        .col-12.col-lg-5.order-1.order-lg-1.mb-4.mb-lg-0(data-aos="fade-left")
          figure.mb-0
            img.mx-auto(src="@/assets/curso/temas/t1/img10.png", data-aos="zoom-in", style="width: 500px; width: 100%;")
        .col-12.col-lg-7.order-2.order-lg-2(data-aos="fade-right")
          p.p-3.bg-color-2.mb-3 La protección de datos personales constituye un elemento estratégico para las organizaciones modernas. Una adecuada gestión de la información fortalece la confianza, promueve la transparencia y contribuye a la sostenibilidad institucional, al tiempo que favorece el cumplimiento de las obligaciones legales relacionadas con el tratamiento de los datos personales.
          p.p-3.bg-color-8.mb-0 Las organizaciones que implementan prácticas responsables de tratamiento de datos mejoran sus procesos internos, reducen riesgos y fortalecen la relación con clientes, usuarios, trabajadores, proveedores y demás grupos de interés. Los principales aspectos que evidencian la importancia organizacional de la protección de datos son los siguientes:
      //- Slideshow
      .bg-full-width.bg-fondo-slider.mb-3
        .p-4.p-md-5
          SlyderA(tipo="b").bg-white.p-4.tarjeta(data-aos="fade-left")
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                 img(src='@/assets/curso/temas/t1/tarjeta04_1.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Confianza y reputación corporativa
                p La confianza constituye uno de los activos más importantes de una organización. Los clientes, usuarios, trabajadores y demás grupos de interés esperan que su información sea tratada de manera segura y responsable. Una adecuada gestión de los datos fortalece la reputación institucional, incrementa la credibilidad y favorece la construcción de relaciones duraderas basadas en la transparencia y el respeto por la privacidad.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t1/tarjeta04_2.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Cumplimiento normativo
                p El cumplimiento de las disposiciones relacionadas con la protección de datos personales permite reducir riesgos legales y prevenir sanciones derivadas del incumplimiento de la normativa vigente. Para ello, las organizaciones deben establecer políticas, procedimientos, controles y mecanismos de seguimiento que garanticen un tratamiento adecuado de la información durante todo su ciclo de vida.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t1/tarjeta04_3.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Responsabilidad institucional
                p La responsabilidad institucional implica promover una cultura organizacional orientada a la protección de la información. Este compromiso involucra a directivos, trabajadores, proveedores, contratistas y terceros que participen en el tratamiento de datos personales. La protección de los datos debe asumirse como una práctica permanente que fortalece la ética organizacional, la seguridad de la información y el respeto por los derechos de los titulares.
      //- Fin Slideshow
      p(data-aos="fade-left") Estos aspectos evidencian que la protección de datos personales trasciende el cumplimiento de una obligación legal y se convierte en un factor que fortalece la gestión organizacional, la confianza institucional y la sostenibilidad de las organizaciones.
      .row.justify-content-center.mb-4(data-aos="fade-left")
        .col-lg-12
          .d-flex.flex-column.flex-lg-row.align-items-center.bg-color-11.p-4.rounded-4
            .flex-shrink-0.mb-3.mb-lg-0.pe-lg-4
              img(src='@/assets/curso/temas/bg/icono-descargar.svg', style="width: 80px")
            .flex-grow-1.text-center.text-lg-start
              h4.mb-2.text-white Actividades de aplicación y análisis de la protección de datos personales
              p.mb-0.text-white Se invita a leer el documento <b>Actividades de aplicación y análisis de la protección de datos personales</b>, donde se aborda la aplicación práctica de los principios, derechos, obligaciones y medidas relacionadas con la protección de datos personales mediante casos de estudio y una actividad de diagnóstico organizacional.
            .mt-3.mt-lg-0.ps-lg-4
              a.btn.btn-custom-download.w-buttons.d-flex.align-items-center.justify-content-center.p-3(:href="obtenerLink('/downloads/Anexos/Anexo_01_Actividades_Proteccion_Datos_Personales.pdf')" target="_blank")
                span.fw-bold.me-2 Descargar
                i.fas.fa-file-download



</template>

<script>
export default {
  name: 'Tema1',
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
