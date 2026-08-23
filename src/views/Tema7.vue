<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido
        .titulo-principal__numero
          span 7
        h1 Vigilancia, control y sanciones
      p.mb-4(data-aos="fade-left") La protección de los datos personales no depende únicamente del compromiso de las organizaciones. Para garantizar el cumplimiento de la Ley 1581 de 2012 existen mecanismos de vigilancia, control y sanción orientados a verificar que los responsables y encargados del tratamiento actúen conforme a la normativa vigente.
      .row.align-items-center.mb-2(data-aos="fade-right")
        .col-lg-8.order-2.order-lg-1
          .row.g-0.align-items-stretch.bg-color-3.mb-4
            .col-12.col-md-5.px-0
              img(src="@/assets/curso/temas/t7/img1.png", style="width:100%; height:100%; object-fit:cover;")
            .col-12.col-md-7.p-4.d-flex.align-items-center
              p.mb-0 Estos mecanismos buscan proteger los derechos de los titulares frente a situaciones como el uso no autorizado de datos personales, la ausencia de políticas de tratamiento, la falta de respuesta a consultas o reclamaciones, la divulgación indebida de información, la pérdida de bases de datos o el incumplimiento de las medidas de seguridad.
          p.mb-0.p-4.bg-color-4 En el contexto organizacional, conocer el funcionamiento de estos mecanismos permite prevenir riesgos legales, fortalecer los controles internos y demostrar el cumplimiento de las obligaciones relacionadas con el tratamiento de datos personales.
        .col-lg-4.order-1.order-lg-2.mb-4.mb-lg-0
          figure.mb-0
            img(src="@/assets/curso/temas/t7/img2.png", data-aos="zoom-in", style="width: 100%; max-width: 300px;").mx-auto
      p(data-aos="fade-left") Además de su función correctiva, la vigilancia y el control cumplen un propósito preventivo, ya que promueven la adopción de buenas prácticas, la mejora continua de los procesos y el fortalecimiento de la cultura organizacional en materia de protección de datos.
      Separador
      //- Inicio Tema7.1
      .row
        #t_7_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
          h2 7.1 Autoridades de control
      .row.align-items-center.mb-4
        .col-12.col-lg-5.order-1.order-lg-2.mb-4.mb-lg-0(data-aos="fade-left")
          figure.mb-0
            img.mx-auto(src="@/assets/curso/temas/t7/img3.png", data-aos="zoom-in", style="width: 500px; width: 100%;")
        .col-12.col-lg-7.order-2.order-lg-1(data-aos="fade-right")
          p.p-3.bg-color-2.mb-3 Las autoridades de control son las entidades encargadas de vigilar el cumplimiento de las normas relacionadas con la protección de datos personales. Su función consiste en verificar que los responsables y encargados del tratamiento respeten los derechos de los titulares y cumplan las obligaciones establecidas por la normativa.
          p.p-3.bg-color-8.rounded-4.mb-0 En Colombia, la Superintendencia de Industria y Comercio (SIC) ejerce la autoridad nacional de protección de datos personales. Entre sus funciones se encuentran recibir quejas, adelantar investigaciones, impartir instrucciones, realizar actividades de inspección y vigilancia, ordenar medidas correctivas e imponer sanciones cuando se evidencien incumplimientos.
      p(data-aos="fade-left") Para las organizaciones, la existencia de una autoridad de control implica la necesidad de conservar evidencias que demuestren el cumplimiento de la normativa. Las políticas, autorizaciones, procedimientos, registros, contratos y controles de seguridad constituyen elementos esenciales para acreditar una gestión adecuada del tratamiento de los datos personales. Los principales aspectos relacionados con las autoridades de control se presentan a continuación:          
      //- Slideshow
      .bg-full-width.bg-fondo-slider.mb-3
        .p-4.p-md-5
          SlyderA(tipo="b").bg-white.p-4.tarjeta(data-aos="fade-left")
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                 img(src='@/assets/curso/temas/t7/tarjeta01_1.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Funciones de supervisión
                p Consisten en verificar que las organizaciones realicen el tratamiento de datos personales conforme a la normativa. La supervisión puede originarse por quejas de los titulares, actuaciones de oficio, requerimientos de información o investigaciones administrativas. Durante este proceso se revisan políticas, autorizaciones, medidas de seguridad, atención de derechos y procedimientos internos para determinar el nivel de cumplimiento de la organización.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t7/tarjeta01_2.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Facultades de inspección
                p Permiten solicitar información, revisar documentos, requerir explicaciones, evaluar procedimientos y verificar las medidas implementadas para proteger los datos personales. Estas actuaciones pueden dar lugar a recomendaciones, requerimientos, medidas correctivas o, cuando corresponda, al inicio de investigaciones administrativas.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t7/tarjeta01_3.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Procesos de investigación
                p Se desarrollan cuando existen indicios de posibles incumplimientos en el tratamiento de datos personales. Durante la investigación se analizan los hechos, las evidencias, las actuaciones de la organización y las posibles afectaciones a los titulares. Como resultado, la autoridad puede ordenar acciones correctivas o imponer las sanciones previstas en la normativa.
      //- Fin Slideshow
      p(data-aos="fade-left") Las principales actividades objeto de supervisión se presentan a continuación:
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
                          img(src='@/assets/curso/temas/t7/tarjeta02_1.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Política de tratamiento de datos personales
                            p.text-center Que exista, se encuentre actualizada y esté disponible para los titulares.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t7/tarjeta02_2.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Autorizaciones
                            p.text-center Que sean previas, expresas, informadas y verificables.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t7/tarjeta02_3.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Finalidad del tratamiento
                            p.text-center Que la información se utilice únicamente para las finalidades informadas al titular.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t7/tarjeta02_4.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Atención de los derechos de los titulares
                            p.text-center Que existan canales de atención y respuestas oportunas a consultas y reclamaciones
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t7/tarjeta02_5.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Seguridad de la información
                            p.text-center Que se implementen medidas técnicas, administrativas y organizacionales para proteger los datos.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t7/tarjeta02_6.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Relación con los encargados del tratamiento
                            p.text-center Que existan contratos, instrucciones y controles sobre los proveedores que tratan datos personales.
                    .col-lg-4.order-lg-1.d-none.d-lg-block
                        figure
                          img(src='@/assets/curso/temas/t7/img4.png', style="width: 500px", data-aos="zoom-in").m-auto
              //- Fin Carrusel
      .row.mb-5.justify-content-center.align-items-center        
        .col-12.col-sm-9.col-lg-5.order-1.order-lg-1.mb-4.mb-lg-0(data-aos="fade-right")
          figure.mb-0.text-center
            img.mx-auto(src='@/assets/curso/temas/t7/img5.png', alt='', style="width: 100%; max-width: 500px;")
        .col-12.col-lg-7.order-2.order-lg-2.bg-color-7.p-4(data-aos="fade-left")
          p.mb-2.fw-bold Ejemplo
          p.mb-0 Una empresa continúa enviando mensajes promocionales a un cliente que previamente solicitó ser retirado de la base de datos comercial. Ante la reclamación presentada, la autoridad de control puede verificar si la organización atendió la solicitud, actualizó la base de datos y conservó las evidencias correspondientes.
      //- Título nivel 3 - Imagen
      .titulo-tercer-nivel.mb-5.mt-3(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/temas/bg/titulos.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 Clasificación según la aptitud productiva
      //- Título nivel 3 - Imagen
      p(data-aos="fade-left") Para facilitar una eventual actividad de supervisión, la organización debe mantener organizada y actualizada la documentación relacionada con la protección de datos personales, incluyendo las autorizaciones, las políticas de tratamiento, los registros de solicitudes, las respuestas suministradas a los titulares, los contratos con encargados y las evidencias de las medidas de seguridad implementadas. Los principales documentos que pueden ser requeridos durante una inspección son los siguientes:
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
                              img(src='@/assets/curso/temas/t7/tarjeta03_1.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Política de tratamiento de datos personales
                            p.text-center Demostrar las reglas generales para el tratamiento de la información.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t7/tarjeta03_2.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Aviso de privacidad
                            p.text-center Evidenciar la información suministrada a los titulares.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t7/tarjeta03_3.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Autorizaciones
                            p.text-center Acreditar el consentimiento otorgado por los titulares cuando sea exigible.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t7/tarjeta03_4.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Inventario de bases de datos
                            p.text-center Identificar la información administrada por la organización.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t7/tarjeta03_5.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Matriz de riesgos
                            p.text-center Evidenciar el análisis y la gestión de riesgos asociados al tratamiento de datos.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t7/tarjeta03_6.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Contratos con encargados
                            p.text-center Demostrar el control ejercido sobre los terceros que procesan datos personales.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t7/tarjeta03_7.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Registro de incidentes
                            p.text-center Documentar los eventos de seguridad y las acciones correctivas implementadas.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t7/tarjeta03_8.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Plan de capacitación
                            p.text-center Evidenciar las actividades de formación realizadas al personal.
                    .col-lg-4.order-lg-1.d-none.d-lg-block
                        figure
                          img(src='@/assets/curso/temas/t7/img6.png', style="width: 500px", data-aos="zoom-in").m-auto
              //- Fin Carrusel
      .bloque-texto-g.bloque-texto-g--inverso.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5
        .bloque-texto-g__img(
          :style="{ backgroundImage: `url(${require_src('@/assets/curso/temas/t7/img7.png')})` }")
        .bloque-texto-g__texto.p-4
          p.mb-0 <b>Ejemplo</b>
            br
            br
            | Una institución educativa recibe un requerimiento para explicar cómo protege los datos personales de sus estudiantes menores de edad. Para responder, presenta las políticas institucionales, las autorizaciones otorgadas por los acudientes, los procedimientos de acceso a las plataformas académicas y las medidas de seguridad implementadas para proteger la información.
      .row.justify-content-center.align-items-center
        .col-12.col-sm-9.col-lg-5.order-1.order-lg-1.mb-4.mb-lg-0(data-aos="fade-right")
          figure.mb-0.text-center
            img.mx-auto(src='@/assets/curso/temas/t7/img8.png', alt='', style="width: 100%; max-width: 450px;")
        .col-12.col-lg-7.order-2.order-lg-2.bg-color-2.p-4(data-aos="fade-left")
          p.fw-bold Aplicación práctica
          p.mb-0 Toda organización debe establecer un procedimiento para atender requerimientos de las autoridades de control. Este procedimiento debe definir quién recibe la comunicación, qué áreas participan en la preparación de la respuesta, cómo se recopilan las evidencias, quién valida la información antes de su envío y cómo se conservan los soportes relacionados con el proceso.
      Separador
      //- Inicio Tema7.2
      .row
        #t_7_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
          h2 7.2 Régimen sancionatorio
      .row.justify-content-center.align-items-stretch.mb-4
        .col-12.col-md-12.col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
          .bg-color-3.p-4.rounded-4.h-100.d-flex.align-items-center
            p.mb-0 El régimen sancionatorio establece las consecuencias que pueden imponerse cuando una organización incumple las obligaciones relacionadas con la protección de datos personales. Su finalidad es corregir prácticas contrarias a la normativa, proteger los derechos de los titulares y promover una gestión responsable de la información.
        .col-12.col-md-12.col-lg-4.mb-4.mb-lg-0(data-aos="zoom-in")
          .h-100.d-flex
            img.rounded-3(src="@/assets/curso/temas/t7/img9.png", style="width: 100%; height: 100%; object-fit: cover;")
        .col-12.col-md-12.col-lg-4(data-aos="fade-left")
          .bg-color-4.p-4.rounded-4.h-100.d-flex.align-items-center
            p.mb-0 Las sanciones pueden derivarse de situaciones como la recolección de datos sin autorización, el uso de información para finalidades diferentes a las informadas, la falta de atención de los derechos de los titulares, el incumplimiento de las medidas de seguridad, la divulgación indebida de datos personales o el desconocimiento de las instrucciones impartidas por la autoridad competente.
      p(data-aos="fade-left") El régimen sancionatorio aplica a cualquier organización que realice tratamiento de datos personales, independientemente de su tamaño o actividad económica. Por ello, resulta fundamental implementar controles preventivos que permitan reducir los riesgos de incumplimiento y fortalecer la cultura institucional de protección de datos. Los principales aspectos relacionados con el régimen sancionatorio se presentan a continuación:
      //- Pestanas horizontales
      .container.tarjeta.tarjeta--blanca.p-4.p-md-5(data-aos="fade-right")
        TabsC.color-acento-contenido.mt-1
          .py-3.py-md-4(titulo="Tipos de infracciones")
            .row.align-items-center
              .col-md-6
                figure
                  img(src='@/assets/curso/temas/t7/tarjeta04_1.png')
              .col-md-6.mb-4.mb-md-0
                h4 Tipos de infracciones
                p Las infracciones corresponden a acciones u omisiones que vulneran los principios, derechos y obligaciones establecidos en la normativa sobre protección de datos personales. Pueden originarse por la recolección indebida de información, la ausencia de autorización, el uso no autorizado de los datos, la falta de atención de los derechos de los titulares, la divulgación de información sin fundamento legal, las fallas de seguridad o el incumplimiento de las órdenes impartidas por la autoridad competente.
          .py-3.py-md-4(titulo="Sanciones aplicables")
            .row.align-items-center
              .col-md-6.mb-4.mb-md-0
                figure
                  img(src='@/assets/curso/temas/t7/tarjeta04_2.png')
              .col-md-6
                h4 Sanciones aplicables
                p Cuando se comprueba un incumplimiento, la autoridad competente puede imponer medidas como multas, órdenes de corrección, suspensión de actividades relacionadas con el tratamiento de datos, cierre temporal de operaciones asociadas a bases de datos y otras actuaciones previstas en la normativa. Además del impacto económico, estas medidas pueden afectar la reputación, la confianza y la continuidad de los procesos organizacionales.
          .py-3.py-md-4(titulo="Medidas correctivas")
            .row.align-items-center
              .col-md-6.mb-4.mb-md-0
                figure
                  img(src='@/assets/curso/temas/t7/tarjeta04_3.png')
              .col-md-6
                h4 Medidas correctivas
                p Corresponden a las acciones implementadas por la organización para eliminar las causas que originaron el incumplimiento y prevenir su repetición. Estas medidas deben documentarse, asignarse a responsables, ejecutarse dentro de plazos definidos y verificarse posteriormente para evaluar su eficacia.
      //- Cierres Pestanas horizontales      
      p(data-aos="fade-left") Las principales infracciones relacionadas con el tratamiento de datos personales se presentan a continuación:
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
                          img(src='@/assets/curso/temas/t7/tarjeta05_1.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Recolección indebida
                            p.text-center Solicitar datos personales sin informar la finalidad del tratamiento.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t7/tarjeta05_2.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Ausencia de autorización
                            p.text-center Utilizar datos personales sin contar con la autorización cuando esta sea exigible.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t7/tarjeta05_3.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Uso no autorizado
                            p.text-center Emplear la información para finalidades diferentes de las informadas al titular.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t7/tarjeta05_4.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Incumplimiento en la atención de derechos
                            p.text-center No responder consultas, reclamaciones o solicitudes de actualización, rectificación o supresión.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t7/tarjeta05_5.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Divulgación indebida
                            p.text-center Compartir datos personales con terceros sin fundamento legal o autorización.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t7/tarjeta05_5.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Falla de seguridad
                            p.text-center Permitir accesos no autorizados, pérdida o alteración de la información.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t7/tarjeta05_5.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Incumplimiento de órdenes
                            p.text-center No atender las instrucciones impartidas por la autoridad competente.
                    .col-lg-4.order-lg-1.d-none.d-lg-block
                        figure
                          img(src='@/assets/curso/temas/t7/img10.png', style="width: 500px", data-aos="zoom-in").m-auto
              //- Fin Carrusel
      .row.mb-5.justify-content-center.align-items-center        
        .col-12.col-sm-9.col-lg-5.order-1.order-lg-2.mb-4.mb-lg-0(data-aos="fade-right")
          figure.mb-0.text-center
            img.mx-auto(src='@/assets/curso/temas/t7/img11.png', alt='', style="width: 100%; max-width: 420px;")
        .col-12.col-lg-7.order-2.order-lg-1.bg-color-7.p-4(data-aos="fade-left")
          p.mb-2.fw-bold Ejemplo
          p.mb-0 Una empresa recopila datos de los asistentes a un evento académico y posteriormente utiliza esa información para enviar publicidad de terceros sin haber informado esa finalidad ni contar con la autorización correspondiente. Esta actuación puede constituir una infracción por utilizar los datos para fines no autorizados.
      //- Título nivel 3 - Imagen
      .titulo-tercer-nivel.mb-5.mt-3(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/temas/bg/titulos.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 Aplicación práctica
      //- Título nivel 3 - Imagen
      p(data-aos="fade-left") Para disminuir el riesgo de sanciones, las organizaciones deben revisar periódicamente sus bases de datos, validar las autorizaciones obtenidas, actualizar sus políticas y procedimientos, capacitar al personal, supervisar el tratamiento realizado por terceros y mantener organizada la documentación que respalde el cumplimiento de la normativa. Las principales medidas correctivas que pueden implementarse frente a hallazgos relacionados con el tratamiento de datos personales son las siguientes:      
      .row.bg-fondo-2(data-aos="fade-right")
        .col-12
          .pt-3.pb-5.px-5
            //- Inicio Tabla
            .row.justify-content-center
              .col-md-auto.col-lg-10
                .titulo-sexto.color-acento-contenido.mb-3
                  h5 Tabla 10.
                  span  Hallazgos frecuentes y medidas correctivas para el cumplimiento de la protección de datos personales
                .tabla-a
                  table
                    thead
                      tr
                        th(style="width: 40%") Hallazgo identificado
                        th(style="width: 60%") Medida correctiva recomendada
                    tbody
                      tr
                        td No existe política de tratamiento de datos personales.
                        td Elaborar, aprobar, publicar y divulgar la política institucional.
                      tr
                        td Autorizaciones incompletas o insuficientes.
                        td Actualizar los formatos y obtener evidencias válidas de autorización.
                      tr
                        td Bases de datos sin soporte documental.
                        td Depurar la información y verificar las finalidades autorizadas.
                      tr
                        td Accesos excesivos a la información.
                        td Implementar una matriz de permisos basada en roles y funciones.
                      tr
                        td Proveedores sin obligaciones relacionadas con protección de datos.
                        td Actualizar los contratos e incorporar cláusulas específicas para los encargados del tratamiento.
                      tr
                        td Personal sin formación en protección de datos.
                        td Desarrollar programas de capacitación y sensibilización.
                      tr
                        td Ausencia de canales para consultas y reclamaciones.
                        td Diseñar e implementar un procedimiento formal para la atención de los titulares.
            //- FinTabla
      Separador
      //- Inicio Tema7.3
      .row
        #t_7_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
          h2 7.3 Gestión del riesgo legal 
      .row.align-items-center.mb-4
        .col-12.col-lg-5.order-1.order-lg-2.mb-4.mb-lg-0(data-aos="fade-left")
          figure.mb-0
            img.mx-auto(src="@/assets/curso/temas/t7/img12.png", data-aos="zoom-in", style="width: 500px; width: 100%;")
        .col-12.col-lg-7.order-2.order-lg-1(data-aos="fade-right")
          p.p-3.bg-color-9.mb-3 La gestión del riesgo legal consiste en identificar, evaluar y controlar las situaciones que pueden generar incumplimientos de la normativa sobre protección de datos personales. Su propósito es prevenir sanciones, proteger los derechos de los titulares y fortalecer el cumplimiento de las obligaciones establecidas en la Ley 1581 de 2012.
          p.p-3.bg-color-11.mb-0 Este enfoque permite anticiparse a los riesgos antes de que se conviertan en incidentes, reclamaciones o investigaciones administrativas. Actividades como revisar periódicamente las bases de datos, validar las autorizaciones, capacitar al personal, supervisar a los encargados del tratamiento y actualizar la documentación contribuyen a reducir la probabilidad de incumplimientos.
      p(data-aos="fade-left") La gestión del riesgo legal debe incorporarse a los procesos organizacionales como una actividad permanente de planificación, seguimiento y mejora continua. De esta manera, la organización fortalece su capacidad para responder oportunamente ante auditorías, requerimientos de las autoridades, incidentes de seguridad o solicitudes presentadas por los titulares. Los principales componentes de la gestión del riesgo legal se presentan a continuación:
      //- Inicio Accordion
      .bg--img_03.mt-5
        .row.justify-content-center
          .col-lg-3.mb-5.mb-lg-0
            figure(data-aos="zoom-in")
              img(src="@/assets/curso/temas/t7/img13.png", alt="").img400.m-auto
          .col-lg-9
            AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta acordeonA")
              .row(titulo="Identificación de riesgos")
                p.mb-4 Consiste en reconocer las situaciones que pueden afectar el cumplimiento de la normativa durante la recolección, el almacenamiento, el uso, la circulación y la eliminación de datos personales. Esta actividad permite priorizar los riesgos según su probabilidad e impacto y definir los controles necesarios para prevenirlos.
              .row(titulo="Prevención de incumplimientos")
                p.mb-4 Comprende la implementación de medidas orientadas a reducir la probabilidad de vulneraciones relacionadas con el tratamiento de datos personales. Estas medidas incluyen la revisión de formularios, la validación de autorizaciones, la capacitación del personal, el control de accesos, la evaluación de proveedores, las auditorías internas y la actualización permanente de políticas y procedimientos.
              .row(titulo="Cultura de protección de datos")
                p.mb-4 Corresponde al conjunto de prácticas, hábitos y comportamientos que promueven la protección permanente de la información dentro de la organización. Esta cultura requiere el compromiso de la alta dirección, la definición de responsabilidades, la formación continua del personal y el fortalecimiento de la conciencia sobre la importancia de proteger los datos personales en todas las actividades institucionales.
      //- Fin Accordion
      p(data-aos="fade-left") La identificación de riesgos permite reconocer las principales situaciones que pueden afectar el tratamiento de los datos personales.
      .row.bg-fondo-2(data-aos="fade-right")
        .col-12
          .pt-3.pb-5.px-5
            //- Inicio Tabla
            .row.justify-content-center.mb-3
              .col-md-auto.col-lg-10
                .titulo-sexto.color-acento-contenido.mb-3
                  h5 Tabla 11.
                  span  Riesgos, causas e impactos en el tratamiento de datos personales
                .tabla-a
                  table
                    thead
                      tr
                        th(style="width: 20%") Riesgo identificado
                        th(style="width: 40%") Posible causa
                        th(style="width: 40%") Impacto
                    tbody
                      tr
                        td Uso de datos sin autorización
                        td Bases de datos antiguas sin soportes de autorización.
                        td Reclamaciones de titulares e investigaciones administrativas.
                      tr
                        td Divulgación indebida de información
                        td Envío de archivos a destinatarios incorrectos.
                        td Vulneración de la privacidad y pérdida de confianza.
                      tr
                        td Acceso no autorizado
                        td Permisos excesivos o controles insuficientes en los sistemas de información.
                        td Exposición de datos personales.
                      tr
                        td Datos desactualizados
                        td Ausencia de procedimientos para la actualización de la información.
                        td Decisiones incorrectas y fallas en las comunicaciones.
                      tr
                        td Proveedores sin controles adecuados
                        td Contratos que no incluyen obligaciones relacionadas con la protección de datos.
                        td Uso indebido de la información por terceros.
                      tr
                        td Pérdida de información
                        td Ausencia de copias de seguridad o fallas en los sistemas.
                        td Interrupción de procesos y afectación de los derechos de los titulares.
            //- FinTabla
      .row.mb-5.justify-content-center.align-items-center        
        .col-12.col-sm-9.col-lg-5.order-1.order-lg-1.mb-4.mb-lg-0(data-aos="fade-right")
          figure.mb-0.text-center
            img.mx-auto(src='@/assets/curso/temas/t7/img14.png', alt='', style="width: 100%; max-width: 450px;")
        .col-12.col-lg-7.order-2.order-lg-2.bg-color-8.p-4(data-aos="fade-left")
          p.mb-2.fw-bold Ejemplo
          p.mb-0 Una empresa identifica que todos los integrantes del área comercial pueden descargar la base completa de clientes sin restricciones. Este hallazgo evidencia un riesgo de acceso excesivo que puede facilitar el uso indebido o la divulgación no autorizada de la información.
      //- Título nivel 3 - Imagen
      .titulo-tercer-nivel.mb-5.mt-3(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/temas/bg/titulos.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 Aplicación práctica
      //- Título nivel 3 - Imagen
      p(data-aos="fade-left") Para identificar los riesgos asociados al tratamiento de datos personales, la organización puede realizar una revisión de cada uno de sus procesos utilizando una matriz de análisis como la siguiente:
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
                              img(src='@/assets/curso/temas/t7/tarjeta06_1.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold ¿Qué datos personales se recopilan?
                            p.text-start Identificar la información objeto de tratamiento.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t7/tarjeta06_2.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold ¿Cuál es la finalidad del tratamiento?
                            p.text-start Verificar que exista una finalidad legítima y documentada.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t7/tarjeta06_3.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold ¿Quién tiene acceso a la información?
                            p.text-start Determinar los usuarios autorizados.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t7/tarjeta06_4.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold ¿Dónde se almacenan los datos?
                            p.text-start Identificar los medios físicos o digitales utilizados.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t7/tarjeta06_5.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold ¿Con quién se comparte la información?
                            p.text-start Verificar la existencia de terceros involucrados en el tratamiento.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t7/tarjeta06_6.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold ¿Qué podría afectar la protección de los datos?
                            p.text-start Identificar amenazas y vulnerabilidades.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t7/tarjeta06_7.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold ¿Qué controles existen actualmente?
                            p.text-start Evaluar las medidas implementadas para reducir los riesgos.
                    .col-lg-4.order-lg-1.d-none.d-lg-block
                        figure
                          img(src='@/assets/curso/temas/t7/img15.png', style="width: 500px", data-aos="zoom-in").m-auto
              //- Fin Carrusel
            p(data-aos="fade-left") Las principales medidas para prevenir incumplimientos relacionados con la protección de datos personales se presentan a continuación:
      .row.bg-fondo-1(data-aos="fade-right")
        .col-12
          .pt-3.pb-5.px-5
            //- Carrusel
            .bg-full-width.mt-5
              .px-4.px-md-5.pb-md-3
                .carousel-bg
                  .row.justify-content-center.mb-5.align-items-center
                    .col-lg-8.mb-3.mb-lg-0.order-lg-1
                      SlyderF(columnas="col-xl-6 col-lg-6")
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t7/tarjeta07_1.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Capacitación periódica del personal
                            p.text-center Fortalecer el conocimiento sobre las obligaciones relacionadas con el tratamiento de datos.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t7/tarjeta07_2.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Revisión de formularios
                            p.text-center Garantizar una recolección de información conforme a la normativa.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t7/tarjeta07_3.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Control de accesos
                            p.text-center Reducir el riesgo de consultas o modificaciones no autorizadas.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t7/tarjeta07_4.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Validación de autorizaciones
                            p.text-center Confirmar que los datos solo se utilicen para las finalidades permitidas.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t7/tarjeta07_5.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Evaluación de proveedores
                            p.text-center Verificar que los encargados del tratamiento implementen medidas adecuadas de protección.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t7/tarjeta07_6.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Auditorías internas
                            p.text-center Detectar oportunamente incumplimientos y oportunidades de mejora.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t7/tarjeta07_7.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Actualización documental
                            p.text-center Mantener vigentes las políticas, procedimientos y demás documentos institucionales.
                    .col-lg-4.order-lg-2.d-none.d-lg-block
                        figure
                          img(src='@/assets/curso/temas/t7/img16.png', style="width: 500px", data-aos="zoom-in").m-auto
              //- Fin Carrusel
      .row.mb-5.justify-content-center.align-items-center        
        .col-12.col-sm-9.col-lg-5.order-1.order-lg-2.mb-4.mb-lg-0(data-aos="fade-right")
          figure.mb-0.text-center
            img.mx-auto(src='@/assets/curso/temas/t7/img17.png', alt='', style="width: 100%; max-width: 450px;")
        .col-12.col-lg-7.order-2.order-lg-1.bg-color-4.p-4(data-aos="fade-left")
          p.mb-2.fw-bold Ejemplo
          p.mb-0 Antes de iniciar una campaña comercial, una empresa revisa las autorizaciones otorgadas por los titulares para recibir comunicaciones promocionales. Los registros que no cuentan con evidencia suficiente son excluidos de la campaña hasta verificar el cumplimiento de las condiciones de legalidad.
      .row.justify-content-center.mb-4(data-aos="fade-left")
        .col-lg-12
          .d-flex.flex-column.flex-lg-row.align-items-center.bg-color-11.p-4.rounded-4
            .flex-shrink-0.mb-3.mb-lg-0.pe-lg-4
              img(src='@/assets/curso/temas/bg/icono-descargar.svg', style="width: 80px")
            .flex-grow-1.text-center.text-lg-start
              h4.mb-2.text-white Protección de datos personales: casos de análisis y práctica sobre cumplimiento normativo
              p.mb-0.text-white Se invita a leer el documento <b>Protección de Datos Personales: Casos de análisis y práctica sobre cumplimiento normativo</b>, donde se abordan situaciones organizacionales relacionadas con el cumplimiento de la Ley 1581 de 2012 mediante casos prácticos enfocados en inspecciones de la autoridad de control, acceso no autorizado a datos sensibles, atención de los derechos de los titulares y uso de bases de datos sin autorización verificable. 
            .mt-3.mt-lg-0.ps-lg-4
              a.btn.btn-custom-download.w-buttons.d-flex.align-items-center.justify-content-center.p-3(:href="obtenerLink('/downloads/Lectura-Programas-técnicos-para-la-prevención-sanitaria.docx')" target="_blank")
                span.fw-bold.me-2 Descargar
                i.fas.fa-file-download
      .row.justify-content-center.mb-4(data-aos="fade-left")
        .col-lg-12
          .d-flex.flex-column.flex-lg-row.align-items-center.bg-color-11.p-4.rounded-4
            .flex-shrink-0.mb-3.mb-lg-0.pe-lg-4
              img(src='@/assets/curso/temas/bg/icono-descargar.svg', style="width: 80px")
            .flex-grow-1.text-center.text-lg-start
              h4.mb-2.text-white Aplicación organizacional de la protección de datos personales
              p.mb-0.text-white Se invita a leer el documento <b>Aplicación organizacional de la protección de datos personales</b>, donde se aborda la implementación práctica de la protección de datos personales en las organizaciones, a partir de las políticas de tratamiento, las medidas administrativas, técnicas y físicas de seguridad, las buenas prácticas y la mejora continua, conforme a la Ley 1581 de 2012. 
            .mt-3.mt-lg-0.ps-lg-4
              a.btn.btn-custom-download.w-buttons.d-flex.align-items-center.justify-content-center.p-3(:href="obtenerLink('/downloads/Lectura-Programas-técnicos-para-la-prevención-sanitaria.docx')" target="_blank")
                span.fw-bold.me-2 Descargar
                i.fas.fa-file-download
</template>

<script>
export default {
  name: 'Tema7',
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
