<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido
        .titulo-principal__numero
          span 5
        h1 Derechos y condiciones de legalidad para el tratamiento de datos
      p(data-aos="fade-left") El tratamiento de datos personales no se limita a la recolección, el almacenamiento o el uso de la información. También implica garantizar que los titulares puedan ejercer control sobre sus datos y que las organizaciones actúen bajo condiciones legales claras, verificables y respetuosas de los derechos fundamentales. En este sentido, la Ley 1581 de 2012 desarrolla el derecho de las personas a conocer, actualizar, rectificar y, cuando corresponda, solicitar la supresión de la información recopilada sobre ellas en bases de datos o archivos.
      .row.align-items-center.mb-5(data-aos="fade-right")
        .col-lg-8.order-2.order-lg-1
          .row.g-0.align-items-stretch.bg-color-6.mb-4
            .col-12.col-md-5.px-0
              img(src="@/assets/curso/temas/t5/img1.png", style="width:100%; height:100%; object-fit:cover;")
            .col-12.col-md-7.p-4.d-flex.align-items-center
              p.mb-0 En el contexto organizacional, el cumplimiento de estas condiciones va más allá de disponer de un aviso de privacidad o de una autorización firmada. También exige demostrar que la información se recopila para finalidades legítimas, que el titular conoce el uso de sus datos, que existen mecanismos para atender consultas y reclamaciones y que se aplican medidas de seguridad durante todo el ciclo de vida de la información.
          p.mb-0.bg-color-10.p-4 El desconocimiento de los derechos de los titulares o el tratamiento de datos sin cumplir los requisitos legales puede generar reclamaciones, investigaciones administrativas, sanciones, pérdida de confianza y afectaciones reputacionales. Por ello, las organizaciones deben implementar procedimientos que garanticen el ejercicio efectivo de estos derechos.
        .col-lg-4.order-1.order-lg-2.mb-4.mb-lg-0
          figure.mb-0
            img(src="@/assets/curso/temas/t5/img2.png", data-aos="zoom-in", style="width: 320px;").mx-auto
      Separador
      //- Inicio Tema5.1
      .row
        #t_5_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
          h2 5.1 Derechos de los titulares 
      .row.align-items-center.mb-4
        .col-12.col-lg-5.order-1.order-lg-2.mb-4.mb-lg-0(data-aos="fade-left")
          figure.mb-0
            img.mx-auto(src="@/assets/curso/temas/t5/img3.png", data-aos="zoom-in", style="width: 500px; width: 100%;")
        .col-12.col-lg-7.order-2.order-lg-1(data-aos="fade-right")
          p.p-3.bg-color-2.mb-3 Los titulares son las personas naturales a quienes pertenecen los datos personales. La normativa les reconoce un conjunto de derechos que les permite mantener el control sobre la información suministrada a entidades públicas, empresas privadas, instituciones educativas, prestadores de servicios, plataformas digitales y demás organizaciones que realizan tratamiento de datos personales.
          p.p-3.bg-color-8.mb-0 El ejercicio de estos derechos exige que las organizaciones cuenten con canales de atención, procedimientos internos, responsables definidos y tiempos de respuesta que permitan atender oportunamente las solicitudes de los titulares. Los principales derechos reconocidos por la Ley 1581 de 2012 se presentan a continuación:
      //- Slideshow
      .bg-full-width.bg-fondo-slider.mb-3
        .p-4.p-md-5
          SlyderA(tipo="b").bg-white.p-4.tarjeta(data-aos="fade-left")
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                 img(src='@/assets/curso/temas/t5/tarjeta01_1.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Conocer la información
                p Permite al titular conocer qué datos personales conserva la organización, las finalidades del tratamiento, el uso de la información y, cuando corresponda, los terceros con quienes ha sido compartida.
                p.mb-3.fw-bold Ejemplo de aplicación
                p Solicitar copia de la información registrada en una base de datos de clientes.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t5/tarjeta01_2.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Actualizar y rectificar datos
                p Permite solicitar la actualización o corrección de información incompleta, inexacta, desactualizada o errónea para garantizar la calidad de los datos personales.
                p.mb-3.fw-bold Ejemplo de aplicación
                p Modificar el número telefónico, la dirección, el correo electrónico o corregir un documento de identidad registrado de forma incorrecta.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t5/tarjeta01_3.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Suprimir información
                p Permite solicitar la eliminación de los datos personales cuando no exista una finalidad legítima para conservarlos o cuando su tratamiento no se ajuste a la normativa.
                p.mb-3.fw-bold Ejemplo de aplicación
                p Solicitar el retiro de los datos de una base utilizada para campañas comerciales.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t5/tarjeta01_4.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Revocar la autorización
                p Permite retirar el consentimiento previamente otorgado para el tratamiento de los datos personales, cuando ello sea procedente conforme a la ley.
                p.mb-3.fw-bold Ejemplo de aplicación
                p Solicitar que la organización deje de enviar comunicaciones promocionales.
      //- Fin Slideshow
      p(data-aos="fade-left") La aplicación de estos derechos fortalece la transparencia, favorece el cumplimiento de la normativa y promueve una relación de confianza entre los titulares y las organizaciones. Los principales aspectos relacionados con el ejercicio de estos derechos se presentan a continuación:
      //- Pestanas horizontales
      .container.tarjeta.tarjeta--blanca.p-4.p-md-5(data-aos="fade-right")
        TabsC.color-acento-contenido.mt-1
          .py-3.py-md-4(titulo="Conocer la información")
            .row.align-items-center
              .col-md-6
                figure
                  img(src='@/assets/curso/temas/t5/tarjeta02_1.png')
              .col-md-6.mb-4.mb-md-0
                h4 Conocer la información
                p El titular puede solicitar información sobre los datos personales que conserva la organización, las finalidades del tratamiento, el uso de la información y los terceros con quienes ha sido compartida, cuando corresponda. Para garantizar este derecho, la organización debe disponer de canales físicos o digitales que permitan atender las consultas de manera clara, verificable y oportuna.
                p.mb-3.fw-bold Aspectos relevantes
                p Favorece la transparencia y permite al titular ejercer control sobre su información personal.
          .py-3.py-md-4(titulo="Actualizar y rectificar datos")
            .row.align-items-center
              .col-md-6.mb-4.mb-md-0
                figure
                  img(src='@/assets/curso/temas/t5/tarjeta02_2.png')
              .col-md-6
                h4 Actualizar y rectificar datos
                p El titular puede solicitar la corrección de datos incompletos, inexactos, desactualizados o erróneos. La organización debe verificar la identidad del solicitante, validar la información suministrada y realizar las actualizaciones en todos los sistemas donde los datos se encuentren registrados.
                p.mb-3.fw-bold Aspectos relevantes
                p Garantiza la calidad de la información y evita errores que puedan afectar decisiones administrativas, comerciales o legales.
          .py-3.py-md-4(titulo="Suprimir información")
            .row.align-items-center
              .col-md-6.mb-4.mb-md-0
                figure
                  img(src='@/assets/curso/temas/t5/tarjeta02_3.png')
              .col-md-6
                h4 Suprimir información
                p El titular puede solicitar la eliminación de sus datos personales cuando ya no sean necesarios para la finalidad autorizada o cuando el tratamiento no se ajuste a la normativa. Antes de atender la solicitud, la organización debe verificar si existen obligaciones legales o contractuales que exijan conservar la información.
                p.mb-3.fw-bold Aspectos relevantes
                p La supresión puede implicar la eliminación, el bloqueo, la anonimización o la restricción del uso de los datos, según cada caso.
      //- Cierres Pestanas horizontales
      p(data-aos="fade-left") Para atender adecuadamente el derecho a conocer la información, las organizaciones deben estar en capacidad de suministrar, como mínimo, la siguiente información:
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
                          img(src='@/assets/curso/temas/t5/tarjeta03_1.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Datos personales almacenados
                            p.text-center Información registrada en las bases de datos institucionales.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t5/tarjeta03_2.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Finalidad del tratamiento
                            p.text-center Motivo por el cual fueron recopilados y son utilizados los datos.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t5/tarjeta03_3.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Autorización otorgada
                            p.text-center Evidencia del consentimiento del titular, cuando sea exigible.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t5/tarjeta03_4.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Uso de la información
                            p.text-center Procesos o actividades en los que se emplean los datos personales.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t5/tarjeta03_5.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Canales de atención
                            p.text-center Medios habilitados para consultas, reclamaciones o ejercicio de derechos.
                    .col-lg-4.order-lg-1.d-none.d-lg-block
                        figure
                          img(src='@/assets/curso/temas/t5/img4.png', style="width: 500px", data-aos="zoom-in").m-auto
              //- Fin Carrusel
      .row.mb-5.justify-content-center.align-items-center
        .col-12.col-sm-9.col-lg-5.order-1.order-lg-2.mb-4.mb-lg-0(data-aos="fade-right")
          figure.mb-0.text-center
            img.mx-auto(src='@/assets/curso/temas/t5/img5.png', alt='', style="width: 100%; max-width: 500px;")
        .col-12.col-lg-7.order-2.order-lg-1.bg-color-4.p-4(data-aos="fade-left")
          p.fw-bold Ejemplo
          p.mb-0 Una persona solicita a una empresa de servicios públicos conocer los datos personales que conserva sobre ella. La organización verifica la identidad del solicitante, consulta sus bases de datos y suministra información sobre los datos registrados, las finalidades del tratamiento y los canales disponibles para ejercer los demás derechos reconocidos por la Ley 1581 de 2012.
      //- Título nivel 3 - Imagen
      .titulo-tercer-nivel.mb-5.mt-3(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/temas/bg/titulos.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 Aplicación práctica
      //- Título nivel 3 - Imagen
      p(data-aos="fade-left") Las respuestas a las consultas de los titulares deben ser específicas, verificables y relacionadas con la información solicitada. Respuestas generales o ambiguas no garantizan el ejercicio efectivo del derecho a conocer la información ni evidencian el cumplimiento del principio de transparencia. Las situaciones más frecuentes relacionadas con el derecho de actualización y rectificación se presentan a continuación:
      .row.bg-fondo-2(data-aos="fade-right")
        .col-12
          .pt-3.pb-5.px-5
            //- Inicio Tabla
            .row.justify-content-center
              .col-md-auto.col-lg-10
                .titulo-sexto.color-acento-contenido.mb-3
                  h5 Tabla 5.
                  span  Riesgos y acciones para la actualización y corrección de datos personales
                .tabla-a
                  table
                    thead
                      tr
                        th(style="width: 20%") Situación
                        th(style="width: 30%") Riesgo si no se corrige
                        th(style="width: 50%") Acción recomendada
                    tbody
                      tr
                        td Correo electrónico desactualizado
                        td Pérdida de comunicaciones importantes.
                        td Actualizar la información en todos los sistemas relacionados.
                      tr
                        td Número de documento incorrecto
                        td Errores en trámites y registros.
                        td Verificar el soporte documental y corregir la información.
                      tr
                        td Dirección física equivocada
                        td Envío de información a personas no autorizadas.
                        td Validar el nuevo dato y actualizar todas las bases correspondientes.
                      tr
                        td Información laboral incompleta
                        td Decisiones administrativas erróneas.
                        td Completar y verificar el expediente con los soportes respectivos.
            //- FinTabla
      Separador
      //- Inicio Tema5.2
      .row
        #t_5_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
          h2 5.2 Autorización para el tratamiento de datos
      p(data-aos="fade-right") La autorización es la manifestación de voluntad mediante la cual el titular permite que sus datos personales sean tratados para una o varias finalidades determinadas. Constituye una de las principales condiciones de legalidad previstas en la Ley 1581 de 2012 y representa una garantía tanto para el titular como para la organización que realiza el tratamiento.
      .row.justify-content-center.align-items-stretch.mb-5
        .col-12.col-md-12.col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
          .bg-color-2.p-4.rounded-4.h-100.d-flex.align-items-center
            p.mb-0 Para que la autorización sea válida, debe obtenerse antes del tratamiento de los datos, expresar de manera clara la aceptación del titular y suministrar información suficiente sobre la finalidad del tratamiento, los derechos que puede ejercer y los canales disponibles para presentar consultas o reclamaciones.
        .col-12.col-md-12.col-lg-4.mb-4.mb-lg-0(data-aos="zoom-in")
          .h-100.d-flex
            img.rounded-3(src="@/assets/curso/temas/t5/img6.png", style="width: 100%; height: 100%; object-fit: cover;")
        .col-12.col-md-12.col-lg-4(data-aos="fade-left")
          .bg-color-8.p-4.rounded-4.h-100.d-flex.align-items-center
            p.mb-0 La autorización no debe entenderse como un requisito meramente documental. Además de obtenerla correctamente, la organización debe conservar la evidencia que demuestre su existencia y garantizar que pueda consultarse cuando sea requerida por el titular o por las autoridades competentes.
      p(data-aos="fade-left") A continuación, se presenta un pódcast sobre la autorización para el tratamiento de datos personales, en el que se describen sus elementos, características, los medios para obtenerla y la importancia de conservar las evidencias que demuestran el consentimiento otorgado por el titular.
      //- Inicio Podcast
      .container-fluid.tarjeta.tarjeta--blanca.px-0.mb-2(data-aos="fade-left")
        .row.g-0.align-items-stretch
          .col-12.col-lg-7.mb-3.mb-lg-0.d-flex
            .p-4.p-md-5.bg-custom-dark-teal.w-100.rounded-4.d-flex.align-items-center
              .row.g-3.align-items-center.w-100
                .col-md-5.text-center.mb-4.mb-md-0
                  img.img-fluid(src="@/assets/curso/temas/bg/podcast.svg" style="max-width: 200px;")
                .col-md-7.ps-md-4
                  h2.mb-3.fw-bold(style="color:#FFF") Pódcast
                  .tarjeta.bg-white.p-3.shadow-sm.border-lemon
                    h5.mb-3.fw-bold Autorización para el tratamiento de datos personales
                    TarjetaAudio.color-primario(
                      texto="" 
                      :audio="podcast1"
                      @audio-hover="mostrarIndicadorTarjetaAudio = false"
                    )
                      .indicador--click(v-if="mostrarIndicadorTarjetaAudio")                      
          .col-12.col-lg-5.d-flex.ps-lg-4
            figure.mb-0.w-100
              img.h-100.w-100(src='@/assets/curso/temas/t5/img7.png' alt='' style="object-fit: cover;")
      //- Fin Podcast
      p.p-4(data-aos="fade-left") Los elementos mínimos que debe contener una autorización se relacionan a continuación:
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
                              img(src='@/assets/curso/temas/t5/tarjeta04_1.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Identificación del titular
                            p.text-center Permite asociar la autorización con una persona determinada.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t5/tarjeta04_2.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Finalidad del tratamiento
                            p.text-center Explica para qué serán utilizados los datos personales.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t5/tarjeta04_3.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Datos objeto del tratamiento
                            p.text-center Indica la información que será recopilada o utilizada.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t5/tarjeta04_4.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Derechos del titular
                            p.text-center Informa los derechos que puede ejercer conforme a la Ley 1581 de 2012.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t5/tarjeta04_5.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Canales de atención
                            p.text-center Señala los medios disponibles para consultas, reclamos y solicitudes.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t5/tarjeta04_6.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Evidencia de la autorización
                            p.text-center Permite demostrar que el titular otorgó su consentimiento.
                    .col-lg-4.order-lg-1.d-none.d-lg-block
                        figure
                          img(src='@/assets/curso/temas/t5/img8.png', style="width: 500px", data-aos="zoom-in").m-auto
              //- Fin Carrusel
            p(data-aos="fade-left") Las características que debe reunir una autorización válida son las siguientes:
      .row.bg-fondo-2(data-aos="fade-right")
        .col-12
          .pt-3.pb-5.px-5
            //- Inicio Tabla
            .row.justify-content-center.mb-5
              .col-md-auto.col-lg-10
                .titulo-sexto.color-acento-contenido.mb-3
                  h5 Tabla 6.
                  span  Características de la autorización para el tratamiento de datos personales
                .tabla-a
                  table
                    thead
                      tr
                        th(style="width: 10%") Característica
                        th(style="width: 40%") Significado
                        th(style="width: 50%") Ejemplo
                    tbody
                      tr
                        td Previa
                        td Se obtiene antes de iniciar el tratamiento de los datos personales.
                        td Solicitar la aceptación antes de registrar la información en un formulario.
                      tr
                        td Expresa
                        td Existe una manifestación clara e inequívoca del titular.
                        td Firma, casilla de aceptación voluntaria o confirmación verificable.
                      tr
                        td Informada
                        td El titular conoce la finalidad, los derechos y las condiciones del tratamiento.
                        td Aviso de privacidad presentado antes de solicitar la autorización.
                      tr
                        td Verificable
                        td Puede demostrarse posteriormente mediante evidencias.
                        td Registro físico o electrónico conservado por la organización.
            //- FinTabla
      .row.justify-content-center.align-items-stretch.mb-5.g-0(data-aos="fade-right")
        .col-lg-5.d-flex
          figure.mb-0.w-100
            img.h-100.w-100(src='@/assets/curso/temas/t5/img9.png', alt='', style="object-fit: cover;")
        .col-lg-7.bg-color-2.d-flex.flex-column.justify-content-center.p-4
          p.fw-bold.mb-2 Ejemplo:
          p.mb-3 Una empresa de capacitación recopila datos de personas interesadas en un curso. Antes de registrar la información, presenta un aviso en el que informa que los datos serán utilizados para gestionar la inscripción, establecer contacto con el participante y enviar información relacionada con la actividad académica. Posteriormente, solicita la aceptación mediante una casilla de consentimiento que el usuario debe seleccionar de manera voluntaria. Los principales medios para obtener la autorización son los siguientes:
          ul.lista-ul.color-vinotinto-custom.mb-0
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Formato físico:</b> utilizado en inscripciones, contratos y trámites presenciales. La evidencia recomendada es el documento firmado y debidamente archivado. 
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Formulario web:</b> empleado para el registro en plataformas y servicios digitales. La evidencia debe incluir la fecha, la hora, la dirección IP, el usuario y el texto de la autorización aceptada. 
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Grabación telefónica:</b> utilizada en procesos de ventas o atención mediante llamadas. La evidencia consiste en el archivo de audio asociado al titular. 
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Correo electrónico:</b> empleado para confirmaciones o solicitudes específicas. La evidencia corresponde al mensaje completo y a la trazabilidad de su envío y recepción. 
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Firma electrónica o digital:</b> utilizada en procesos electrónicos formales. La evidencia incluye el certificado, el registro o el documento firmado electrónicamente.
      .bloque-texto-g.bloque-texto-g--inverso.color-secundario.p-3.p-sm-4.p-md-5.mb-5
        .bloque-texto-g__img(
          :style="{ backgroundImage: `url(${require_src('@/assets/curso/temas/t5/img10.png')})` }")
        .bloque-texto-g__texto.p-4
          p.mb-0 <b>Aplicación práctica</b>
            br
            br
            | Al seleccionar el mecanismo para obtener la autorización, la organización debe considerar el tipo de información que será tratada y el nivel de riesgo asociado. Para datos básicos puede ser suficiente un formulario claro y verificable; en el caso de datos sensibles, es recomendable utilizar mecanismos de autenticación y conservación de evidencias que ofrezcan mayores garantías de seguridad y trazabilidad.
      p(data-aos="fade-left") Las principales evidencias que permiten demostrar la autorización se presentan a continuación:
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
                          img(src='@/assets/curso/temas/t5/tarjeta05_1.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Formato firmado
                            p.text-center Nombre del titular, fecha, finalidad, firma y versión del documento.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t5/tarjeta05_2.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Registro web
                            p.text-center Usuario, fecha, hora, dirección IP, finalidad aceptada y evidencia del consentimiento.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t5/tarjeta05_3.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Grabación
                            p.text-center Identificación del titular, información suministrada y aceptación manifestada.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t5/tarjeta05_4.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Correo electrónico
                            p.text-center Mensaje enviado, respuesta del titular y trazabilidad de la comunicación.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t5/tarjeta05_5.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Contrato
                            p.text-center Cláusula de tratamiento de datos, aceptación y fecha de suscripción.
                    .col-lg-4.order-lg-1.d-none.d-lg-block
                        figure
                          img(src='@/assets/curso/temas/t5/img11.png', style="width: 500px", data-aos="zoom-in").m-auto
              //- Fin Carrusel
            Separador
            //- Inicio Tema5.3
            .row
              #t_5_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
                h2 5.3 Condiciones de legalidad 
            .row.align-items-center(data-aos="fade-right")
              .col-lg-8.order-2.order-lg-1
                .row.g-0.align-items-stretch.bg-color-2.mb-4
                  .col-12.col-md-5.px-0
                    img(src="@/assets/curso/temas/t5/img12.png", style="width:100%; height:100%; object-fit:cover;")
                  .col-12.col-md-7.p-4.d-flex.align-items-center
                    p.mb-0 Las condiciones de legalidad corresponden a los requisitos que permiten determinar si el tratamiento de datos personales se realiza conforme a la Ley 1581 de 2012 y a las demás disposiciones aplicables. Estas condiciones garantizan que la recolección, el uso, el almacenamiento, la circulación, la conservación y la supresión de la información respeten los derechos de los titulares y respondan a una finalidad legítima.
                p.mb-3 Una organización puede disponer de procesos bien estructurados y herramientas tecnológicas avanzadas; sin embargo, si recopila información sin autorización, la utiliza para finalidades diferentes a las informadas o no garantiza el ejercicio de los derechos de los titulares, el tratamiento puede resultar contrario a la normativa.
                pmb-0 La verificación de las condiciones de legalidad debe realizarse antes de iniciar el tratamiento, durante su ejecución y al finalizar el ciclo de vida de los datos personales. Este proceso permite identificar riesgos, prevenir incumplimientos y fortalecer la gestión de la información. Los principales aspectos relacionados con las condiciones de legalidad se presentan a continuación:
              .col-lg-4.order-1.order-lg-2.mb-4.mb-lg-0
                figure.mb-0
                  img(src="@/assets/curso/temas/t5/img13.png", data-aos="zoom-in", style="width: 100%; max-width: 380px;").mx-auto
      //- Slideshow
      .bg-full-width.bg-fondo-slider.mb-3
        .p-4.p-md-5
          SlyderA(tipo="b").bg-white.p-4.tarjeta(data-aos="fade-left")
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                 img(src='@/assets/curso/temas/t5/tarjeta06_1.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Condiciones de legalidad
                p El tratamiento de datos personales debe sustentarse en una finalidad legítima, contar con la autorización cuando sea exigible, informar previamente al titular sobre el tratamiento, aplicar el principio de proporcionalidad, proteger la información mediante medidas de seguridad y garantizar canales para el ejercicio de los derechos de los titulares.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t5/tarjeta06_2.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Tratamiento autorizado
                p Existe cuando la organización cuenta con una base legal válida para tratar los datos personales y respeta los límites de la autorización otorgada por el titular. El uso de la información debe ser coherente con la finalidad informada y respaldarse mediante evidencias que permitan demostrar el cumplimiento de la normativa.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t5/tarjeta06_3.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Tratamiento sin autorización
                p Se presenta cuando la organización recopila, utiliza, conserva o comparte datos personales sin autorización del titular o sin otra condición legal que habilite el tratamiento. También ocurre cuando los datos se utilizan para finalidades diferentes de aquellas informadas inicialmente.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t5/tarjeta06_4.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Consecuencias del incumplimiento
                p El incumplimiento de las condiciones de legalidad puede generar investigaciones administrativas, sanciones, pérdidas económicas, afectaciones reputacionales, interrupciones operativas y vulneraciones de los derechos de los titulares.
      //- Fin Slideshow
      p(data-aos="fade-left") Las principales condiciones que deben verificarse antes de realizar el tratamiento de datos personales son las siguientes:
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
                          img(src='@/assets/curso/temas/t5/tarjeta07_1.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Finalidad legítima
                            p.text-center ¿Existe una razón clara, específica y válida para tratar los datos personales?
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t5/tarjeta07_2.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Autorización
                            p.text-center ¿El titular otorgó autorización cuando la normativa lo exige?
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t5/tarjeta07_3.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Información previa
                            p.text-center ¿El titular recibió información suficiente sobre el tratamiento de sus datos?
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t5/tarjeta07_4.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Proporcionalidad
                            p.text-center ¿Solo se recopilan los datos estrictamente necesarios para la finalidad prevista?
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t5/tarjeta07_5.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Seguridad
                            p.text-center ¿La información cuenta con medidas de protección adecuadas?
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t5/tarjeta07_5.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Atención de derechos
                            p.text-center ¿La organización dispone de canales para atender consultas, reclamos y solicitudes?                            
                    .col-lg-4.order-lg-1.d-none.d-lg-block
                        figure
                          img(src='@/assets/curso/temas/t5/img14.png', style="width: 500px", data-aos="zoom-in").m-auto
              //- Fin Carrusel
      .bloque-texto-g.bloque-texto-g--inverso.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5
        .bloque-texto-g__img(
          :style="{ backgroundImage: `url(${require_src('@/assets/curso/temas/t5/img15.png')})` }")
        .bloque-texto-g__texto.p-4
          p.mb-0 La aplicación de estas condiciones permite demostrar que el tratamiento de los datos personales se desarrolla conforme a los principios de legalidad, finalidad, transparencia y responsabilidad. Los elementos que caracterizan un tratamiento autorizado se presentan a continuación:
            ul.lista-ul.color-vinotinto-custom.mb-0
              li.d-flex.mt-3
                .fas.fa-check-circle.me-3
                span <b>Finalidad:</b> definir un propósito claro, específico y conocido por el titular antes de realizar el tratamiento de los datos personales.    
              li.d-flex.mt-3
                .fas.fa-check-circle.me-3
                span <b>Autorización:</b> obtener y conservar una autorización previa, expresa, informada y verificable, cuando sea exigible.
              li.d-flex.mt-3
                .fas.fa-check-circle.me-3
                span <b>Uso de los datos:</b> garantizar que la información se utilice únicamente para la finalidad autorizada por el titular o permitida por la ley.
              li.d-flex.mt-3
                .fas.fa-check-circle.me-3
                span <b>Acceso interno:</b> restringir el acceso a los datos personales exclusivamente al personal autorizado según sus funciones.
              li.d-flex.mt-3
                .fas.fa-check-circle.me-3
                span <b>Evidencia:</b> conservar los soportes y registros necesarios para demostrar el cumplimiento de las obligaciones en procesos de verificación o auditoría.      
      .row.mb-5.justify-content-center.align-items-center        
        .col-12.col-sm-9.col-lg-5.order-1.order-lg-1.mb-4.mb-lg-0(data-aos="fade-right")
          figure.mb-0.text-center
            img.mx-auto(src='@/assets/curso/temas/t5/img16.png', alt='', style="width: 100%; max-width: 500px;")
        .col-12.col-lg-7.order-2.order-lg-2.bg-color-4.p-4(data-aos="fade-left")
          p.fw-bold  Ejemplo
          p.mb-0 Una tienda virtual solicita el nombre, la dirección, el número telefónico y el correo electrónico de sus clientes para gestionar la compra y realizar la entrega de un producto. Cuando informa claramente esta finalidad y obtiene la autorización correspondiente, puede utilizar los datos para ejecutar el proceso de venta. Si posteriormente desea enviar campañas publicitarias, deberá contar con una autorización específica para esa nueva finalidad.
      .row.mb-5.justify-content-center.align-items-center        
        .col-12.col-sm-9.col-lg-5.order-1.order-lg-2.mb-4.mb-lg-0(data-aos="fade-right")
          figure.mb-0.text-center
            img.mx-auto(src='@/assets/curso/temas/t5/img17.png', alt='', style="width: 100%; max-width: 500px;")
        .col-12.col-lg-7.order-2.order-lg-1.bg-color-9.p-4(data-aos="fade-left")
          p.fw-bold Aplicación práctica
          p.mb-0 Antes de utilizar una base de datos para una nueva campaña comercial, la organización debe verificar que la finalidad correspondiente haya sido autorizada por los titulares. Si no existe evidencia suficiente, deberá abstenerse de utilizar la información hasta obtener la autorización requerida o identificar otra base legal que permita el tratamiento.
      p(data-aos="fade-left") Las situaciones más frecuentes relacionadas con el tratamiento sin autorización se presentan a continuación:
      .row.bg-fondo-2(data-aos="fade-right")
        .col-12
          .pt-3.pb-5.px-5
            //- Inicio Tabla
            .row.justify-content-center.mb-5
              .col-md-auto.col-lg-10
                .titulo-sexto.color-acento-contenido.mb-3
                  h5 Tabla 7.
                  span Riesgos y acciones para garantizar una autorización válida en el tratamiento de datos personales
                .tabla-a
                  table
                    thead
                      tr
                        th(style="width: 20%") Situación
                        th(style="width: 40%") Riesgo asociado
                        th(style="width: 40%") Acción recomendada
                    tbody
                      tr
                        td Compra de una base de datos sin soporte.
                        td Uso de información sin consentimiento.
                        td Verificar el origen de la información y las autorizaciones antes de utilizarla.
                      tr
                        td Envío de publicidad sin autorización.
                        td Reclamaciones por uso indebido de datos personales.
                        td Obtener autorización específica o excluir los contactos de las campañas.
                      tr
                        td Compartir datos con terceros sin respaldo legal.
                        td Divulgación no autorizada de información personal.
                        td Formalizar la autorización correspondiente o contar con otra base legal válida.
                      tr
                        td Formularios sin información sobre la finalidad.
                        td Falta de transparencia en el tratamiento.
                        td Ajustar los formatos e incorporar la información requerida por la normativa.
                      tr
                        td Uso de datos para finalidades diferentes a las autorizadas.
                        td Incumplimiento del principio de finalidad.
                        td Obtener una nueva autorización antes de realizar el tratamiento adicional.
            //- FinTabla                    
      .row.justify-content-center.mb-4(data-aos="fade-left")
        .col-lg-12
          .d-flex.flex-column.flex-lg-row.align-items-center.bg-color-11.p-4.rounded-4
            .flex-shrink-0.mb-3.mb-lg-0.pe-lg-4
              img(src='@/assets/curso/temas/bg/icono-descargar-5.svg', style="width: 80px")
            .flex-grow-1.text-center.text-lg-start
              h4.mb-2.text-white Actividades de aplicación y análisis de los derechos de los titulares y las condiciones de legalidad
              p.mb-0.text-white Se invita a leer el documento <b>Actividades de aplicación y análisis de los derechos de los titulares y las condiciones de legalidad</b>, donde se aborda la aplicación práctica de los derechos de los titulares, la autorización para el tratamiento de datos personales y las condiciones de legalidad establecidas en la Ley 1581 de 2012.
            .mt-3.mt-lg-0.ps-lg-4
              a.btn.btn-custom-download.w-buttons.d-flex.align-items-center.justify-content-center.p-3(:href="obtenerLink('/downloads/Lectura-Programas-técnicos-para-la-prevención-sanitaria.docx')" target="_blank")
                span.fw-bold.me-2 Descargar
                i.fas.fa-file-download                  
</template>

<script>
import podcast1 from '@/assets/curso/temas/audio/podcast.mp3'
export default {
  name: 'Tema5',
  data: () => ({
    podcast1,
    mostrarIndicadorTarjetaAudio: true,
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
