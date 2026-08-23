<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido
        .titulo-principal__numero
          span 6
        h1 Responsables y encargados del tratamiento
      .row.justify-content-center.align-items-stretch
        .col-12.col-md-12.col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
          .bg-color-6.p-4.rounded-4.h-100.d-flex.align-items-center
            p.mb-0 El tratamiento de datos personales dentro de una organización involucra diferentes personas, áreas, proveedores, sistemas y terceros que participan en la recolección, el almacenamiento, el uso, la circulación, la actualización y la supresión de la información. Por esta razón, es indispensable identificar quién toma las decisiones sobre los datos, quién ejecuta las actividades de tratamiento y cuáles son las responsabilidades que corresponden a cada actor.
        .col-12.col-md-12.col-lg-4.mb-4.mb-lg-0(data-aos="zoom-in")
          .h-100.d-flex
            img.rounded-3(src="@/assets/curso/temas/t6/img1.png", style="width: 100%; height: 100%; object-fit: cover;")
        .col-12.col-md-12.col-lg-4(data-aos="fade-left")
          .bg-color-7.p-4.rounded-4.h-100.d-flex.align-items-center
            p.mb-0 La Ley 1581 de 2012 establece dos figuras fundamentales para la gestión de los datos personales: el <b>responsable del tratamiento</b> y el <b>encargado del tratamiento</b>. Esta diferenciación permite definir quién determina las finalidades y condiciones del tratamiento y quién desarrolla las actividades sobre los datos siguiendo las instrucciones del responsable. La correcta identificación de estos roles facilita el cumplimiento de la normativa, fortalece la protección de la información y permite atender adecuadamente los derechos de los titulares.
      Separador
      //- Inicio Tema6.1
      .row
        #t_6_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
          h2 6.1 Responsable del tratamiento 
      .row.align-items-center.mb-4
        .col-12.col-lg-5.order-1.order-lg-2.mb-4.mb-lg-0(data-aos="fade-left")
          figure.mb-0
            img.mx-auto(src="@/assets/curso/temas/t6/img2.png", data-aos="zoom-in", style="width: 600px; width: 100%;")
        .col-12.col-lg-7.order-2.order-lg-1(data-aos="fade-right")
          p.p-2.bg-color-2.mb-3 El responsable del tratamiento es la persona natural o jurídica, pública o privada, que decide sobre la base de datos o sobre el tratamiento de los datos personales. Es quien determina qué información se recopila, con qué finalidad se utiliza, durante cuánto tiempo se conserva y bajo qué condiciones puede compartirse.
          p.p-2.bg-color-8.mb-0 Aunque una organización delegue actividades operativas en proveedores o terceros, continúa siendo responsable frente a los titulares cuando mantiene el control sobre las finalidades y las decisiones relacionadas con el tratamiento de los datos personales. Los principales aspectos relacionados con el responsable del tratamiento se presentan a continuación:
      //- Slideshow
      .bg-full-width.bg-fondo-slider.mb-3
        .p-4.p-md-5
          SlyderA(tipo="b").bg-white.p-4.tarjeta(data-aos="fade-left")
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                 img(src='@/assets/curso/temas/t6/tarjeta01_1.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Concepto y alcance
                p El responsable del tratamiento es quien define las finalidades, los medios y las condiciones para el tratamiento de los datos personales. Su responsabilidad comprende todas las etapas del ciclo de vida de la información, desde la recolección hasta la supresión de los datos, garantizando el cumplimiento de la Ley 1581 de 2012 y la protección de los derechos de los titulares.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t6/tarjeta01_2.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Funciones principales
                p Entre sus funciones se encuentran definir la finalidad del tratamiento, informar al titular sobre el uso de sus datos, obtener la autorización cuando sea necesaria, conservar las evidencias correspondientes, garantizar el ejercicio de los derechos de los titulares, implementar medidas de seguridad y supervisar el cumplimiento de las obligaciones por parte de los encargados del tratamiento.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t6/tarjeta01_3.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Obligaciones legales
                p El responsable debe garantizar que el tratamiento se realice conforme a la normativa, proteger la información, conservar las autorizaciones, atender consultas y reclamaciones, actualizar los datos cuando corresponda, supervisar a los encargados y demostrar el cumplimiento de las disposiciones legales mediante políticas, procedimientos y controles adecuados.
      //- Fin Slideshow
      p(data-aos="fade-left") Los principales elementos que caracterizan al responsable del tratamiento se presentan a continuación:

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
                              img(src='@/assets/curso/temas/t6/tarjeta02_1.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Quién es
                            p.text-center Persona natural o jurídica, pública o privada, que decide sobre el tratamiento de los datos personales.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t6/tarjeta02_2.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Qué define
                            p.text-center Las finalidades, los medios de tratamiento, la conservación y la circulación de los datos.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t6/tarjeta02_3.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Frente a quién responde
                            p.text-center Frente a los titulares de los datos y las autoridades competentes.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t6/tarjeta02_4.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Responsabilidad principal
                            p.text-center Garantizar el cumplimiento de la normativa sobre protección de datos personales.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t6/tarjeta02_5.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Ejemplo
                            p.text-center Empresa que recopila datos de clientes para prestar un servicio.
                    .col-lg-4.order-lg-1.d-none.d-lg-block
                        figure
                          img(src='@/assets/curso/temas/t6/img3.png', style="width: 500px", data-aos="zoom-in").m-auto
              //- Fin Carrusel
            .row.mb-5.justify-content-center.align-items-center        
              .col-12.col-sm-9.col-lg-5.order-1.order-lg-1.mb-4.mb-lg-0(data-aos="fade-right")
                figure.mb-0.text-center
                  img.mx-auto(src='@/assets/curso/temas/t6/img4.png', alt='', style="width: 100%; max-width: 500px;")
              .col-12.col-lg-7.order-2.order-lg-2.bg-color-4.p-4(data-aos="fade-left")
                p.mb-2.fw-bold Ejemplo
                p.mb-0 Una empresa de comercio electrónico solicita el nombre, la dirección, el teléfono, el correo electrónico y los datos necesarios para procesar las compras de sus clientes. Como define qué información recopila, con qué finalidad la utiliza y cómo será administrada, actúa como responsable del tratamiento.
            //- Título nivel 3 - Imagen
            .titulo-tercer-nivel.mb-5.mt-3(data-aos="fade-right")
              img.titulo-tercer-nivel__icon(src='@/assets/curso/temas/bg/titulos.svg')
              h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 Aplicación práctica
            //- Título nivel 3 - Imagen
            p(data-aos="fade-left") Antes de iniciar un nuevo tratamiento de datos personales, el responsable puede utilizar una matriz de verificación como la siguiente para comprobar el cumplimiento de sus obligaciones:
      .row.bg-fondo-2(data-aos="fade-right")
        .col-12
          .pt-3.pb-5.px-5
            //- Inicio Tabla
            .row.justify-content-center
              .col-md-auto.col-lg-10
                .titulo-sexto.color-acento-contenido.mb-3
                  h5 Tabla 8.
                  span  Lista de verificación para el cumplimiento del tratamiento de datos personales
                .tabla-a
                  table
                    thead
                      tr
                        th(style="width: 30%") Pregunta de verificación
                        th(style="width: 10%") Sí
                        th(style="width: 10%") No
                        th(style="width: 50%") Acción requerida
                    tbody
                      tr
                        td ¿La finalidad del tratamiento está claramente definida?
                        td 
                        td 
                        td Definir y documentar una finalidad específica.
                      tr
                        td ¿Solo se recopilan los datos estrictamente necesarios?
                        td 
                        td 
                        td Eliminar la información que no resulte pertinente.
                      tr
                        td ¿Existe autorización cuando la normativa la exige?
                        td 
                        td 
                        td Implementar un mecanismo de obtención de autorizaciones.
                      tr
                        td ¿Se conserva evidencia del consentimiento?
                        td 
                        td 
                        td Organizar un repositorio de soportes y registros.
                      tr
                        td ¿Existe un canal para consultas y reclamaciones?
                        td 
                        td 
                        td Designar responsables y establecer procedimientos de atención.
                      tr
                        td ¿Se aplican medidas de seguridad sobre la información?
                        td 
                        td 
                        td Implementar controles técnicos, administrativos y organizacionales.
            //- FinTabla
      Separador
      //- Inicio Tema6.2
      .row
        #t_6_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
          h2 6.2 Encargado del tratamiento 
      p.mb-4(data-aos="fade-left") El encargado del tratamiento es la persona natural o jurídica, pública o privada, que realiza el tratamiento de datos personales por cuenta del responsable. A diferencia del responsable, el encargado no define la finalidad del tratamiento, sino que ejecuta las actividades relacionadas con los datos siguiendo las instrucciones recibidas.
      .row.align-items-center.mb-3(data-aos="fade-right")
        .col-lg-8.order-2.order-lg-1
          .row.g-0.align-items-stretch.bg-color-6.mb-4
            .col-12.col-md-5.px-0
              img(src="@/assets/curso/temas/t6/img5.png", style="width:100%; height:100%; object-fit:cover;")
            .col-12.col-md-7.p-4.d-flex.align-items-center
              p.mb-0 Esta figura es frecuente cuando las organizaciones contratan proveedores tecnológicos, empresas de archivo, servicios de nómina, plataformas de correo electrónico, sistemas de gestión académica, servicios de almacenamiento en la nube, empresas de mensajería, call centers u otras entidades que requieren acceso a datos personales para prestar un servicio.
          p.mb-0.bg-color-7.p-4 Aunque el encargado no determina la finalidad del tratamiento, tiene obligaciones específicas relacionadas con la protección de la información. Entre ellas se encuentran garantizar la confidencialidad, aplicar medidas de seguridad, cumplir las instrucciones impartidas por el responsable y abstenerse de utilizar los datos para fines distintos de los autorizados.
        .col-lg-4.order-1.order-lg-2.mb-4.mb-lg-0
          figure.mb-0
            img(src="@/assets/curso/temas/t6/img6.png", data-aos="zoom-in", style="width: 100%; max-width: 310px;").mx-auto
      p(data-aos="fade-left") La relación entre el responsable y el encargado debe formalizarse mediante documentos que definan las responsabilidades, las condiciones del tratamiento, las medidas de seguridad y las actuaciones que deberán realizarse al finalizar la relación contractual. Los principales aspectos relacionados con el encargado del tratamiento se presentan a continuación:
      //- Slideshow
      .bg-full-width.bg-fondo-slider.mb-3
        .p-4.p-md-5
          SlyderA(tipo="b").bg-white.p-4.tarjeta(data-aos="fade-left")
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                 img(src='@/assets/curso/temas/t6/tarjeta03_1.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Concepto y alcance
                p El encargado del tratamiento realiza operaciones sobre los datos personales por cuenta del responsable y conforme a sus instrucciones. Su intervención puede comprender actividades como el almacenamiento de información, la administración de plataformas, el procesamiento de nómina, la custodia documental, el soporte tecnológico o cualquier otra labor que implique acceso a datos personales. No puede utilizar la información para finalidades propias ni conservarla una vez finalice la prestación del servicio, salvo que exista una obligación legal o una instrucción expresa del responsable.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t6/tarjeta03_2.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Responsabilidades operativas
                p El encargado debe tratar los datos únicamente para cumplir el servicio contratado, proteger la información mediante medidas técnicas, administrativas y organizacionales, mantener la confidencialidad, limitar el acceso al personal autorizado, informar oportunamente los incidentes de seguridad y apoyar al responsable en la atención de consultas y solicitudes de los titulares.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t6/tarjeta03_3.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Relación con el responsable
                p La relación entre ambas partes debe sustentarse en contratos, acuerdos de tratamiento de datos, cláusulas de confidencialidad y demás documentos que definan las instrucciones, los controles de seguridad, las responsabilidades de cada parte y el procedimiento para la devolución, eliminación o bloqueo de la información cuando finalice el contrato.
      //- Fin Slideshow
      .row.justify-content-center.align-items-stretch.mb-5.g-0(data-aos="fade-right")
        .col-lg-5.d-flex
          figure.mb-0.w-100
            img.h-100.w-100(src='@/assets/curso/temas/t6/img7.png', alt='', style="object-fit: cover;")
        .col-lg-7.bg-color-2.d-flex.flex-column.justify-content-center.p-4          
          p.mb-3 Los principales elementos que caracterizan al encargado del tratamiento se presentan a continuación:
          ul.lista-ul.color-vinotinto-custom.mb-0
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Quién es:</b> persona natural o jurídica que realiza el tratamiento de datos personales por cuenta del responsable del tratamiento.
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Qué hace:</b> ejecuta las operaciones de recolección, almacenamiento, uso, circulación o supresión de los datos personales conforme a las instrucciones recibidas.
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Qué no debe hacer:</b> definir finalidades propias ni utilizar los datos personales para fines distintos a los autorizados o instruidos por el responsable.
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Fuente de instrucciones:</b> actúa de acuerdo con las directrices impartidas por el responsable del tratamiento.
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Ejemplo:</b> proveedor que administra una base de datos de clientes en una plataforma de almacenamiento en la nube por cuenta de una organización.
      .row.mb-5.justify-content-center.align-items-center
        .col-12.col-sm-9.col-lg-5.order-1.order-lg-2.mb-4.mb-lg-0(data-aos="fade-right")
          figure.mb-0.text-center
            img.mx-auto(src='@/assets/curso/temas/t6/img8.png', alt='', style="width: 100%; max-width: 450px;")
        .col-12.col-lg-7.order-2.order-lg-1.bg-color-4.p-4(data-aos="fade-left")
          p.mb-2.fw-bold Ejemplo
          p.mb-0 Una empresa contrata un proveedor de software para administrar la nómina de sus trabajadores. El proveedor procesa información laboral y financiera siguiendo las instrucciones impartidas por la empresa. En este caso, el proveedor actúa como encargado del tratamiento.
      p(data-aos="fade-left") Las principales responsabilidades del encargado del tratamiento son las siguientes:
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
                          img(src='@/assets/curso/temas/t6/tarjeta04_1.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Seguir las instrucciones del responsable
                            p.text-center Utilizar los datos únicamente para prestar el servicio contratado.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t6/tarjeta04_2.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Garantizar la seguridad de la información
                            p.text-center Implementar controles de acceso, cifrado, copias de respaldo y demás medidas de protección.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t6/tarjeta04_3.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Mantener la confidencialidad
                            p.text-center Evitar la divulgación o el uso no autorizado de la información.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t6/tarjeta04_4.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Reportar incidentes de seguridad
                            p.text-center Informar oportunamente cualquier situación que pueda afectar la protección de los datos personales.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t6/tarjeta04_5.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Limitar los accesos internos
                            p.text-center Permitir el acceso únicamente al personal autorizado para desarrollar el servicio.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t6/tarjeta04_6.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Devolver, eliminar o bloquear la información
                            p.text-center Cumplir las instrucciones del responsable cuando finalice la relación contractual.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t6/tarjeta04_7.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Apoyar la atención de los derechos de los titulares
                            p.text-center Facilitar la información necesaria para atender consultas, reclamaciones y demás solicitudes.
                    .col-lg-4.order-lg-1.d-none.d-lg-block
                        figure
                          img(src='@/assets/curso/temas/t6/img9.png', style="width: 500px", data-aos="zoom-in").m-auto
              //- Fin Carrusel
      //- Título nivel 3 - Imagen
      .titulo-tercer-nivel.mb-5.mt-3(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/temas/bg/titulos.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 Aplicación práctica
      //- Título nivel 3 - Imagen
      .bloque-texto-g.bg-color-5.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-left")
        .bloque-texto-g__img(
          :style="{ backgroundImage: `url(${require_src('@/assets/curso/temas/t6/img10.png')})` }")
        .bloque-texto-g__texto.p-4
          p.mb-0 Antes de contratar un proveedor que tendrá acceso a datos personales, la organización debe verificar los siguientes aspectos:
            br
            br
          ul.lista-ul.color-vinotinto-custom.mb-0
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Datos personales a los que tendrá acceso el proveedor:</b> definir el tipo y el alcance de la información que podrá tratar durante la ejecución del contrato.
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Finalidad del acceso:</b> verificar que el tratamiento de los datos responda exclusivamente al servicio contratado y a las instrucciones del responsable.
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Medidas de seguridad implementadas:</b> confirmar que el proveedor aplica controles técnicos, administrativos y organizacionales adecuados para proteger la información.
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Personal autorizado para acceder a los datos:</b> limitar el acceso únicamente a las personas que lo requieran para el cumplimiento de sus funciones.
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Tratamiento de la información al finalizar el contrato:</b> establecer si los datos personales serán devueltos, eliminados o bloqueados una vez concluida la relación contractual.
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Gestión de incidentes de seguridad:</b> definir el procedimiento para reportar, atender y documentar los incidentes que puedan afectar la información.
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Acuerdos de confidencialidad y tratamiento de datos:</b> formalizar las obligaciones, responsabilidades y compromisos de las partes respecto a la protección de los datos personales.
      Separador
      //- Inicio Tema6.3
      .row
        #t_6_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
          h2 6.3 Gestión organizacional del tratamiento de datos
      .row.justify-content-center.align-items-stretch.mb-5
        .col-12.col-md-12.col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
          .bg-color-2.p-4.rounded-4.h-100.d-flex.align-items-center
            p.mb-0 La gestión organizacional del tratamiento de datos comprende el conjunto de roles, procedimientos, controles y documentos que permiten administrar la información personal de manera organizada, segura y conforme a la Ley 1581 de 2012. Su propósito es integrar la protección de datos a los procesos cotidianos de la organización y garantizar que el cumplimiento normativo se refleje en las actividades diarias.
        .col-12.col-md-12.col-lg-4.mb-4.mb-lg-0(data-aos="zoom-in")
          .h-100.d-flex
            img.rounded-3(src="@/assets/curso/temas/t6/img11.png", style="width: 100%; height: 100%; object-fit: cover;")
        .col-12.col-md-12.col-lg-4(data-aos="fade-left")
          .bg-color-8.p-4.rounded-4.h-100.d-flex.align-items-center
            p.mb-0 Contar con políticas institucionales no es suficiente si no existen responsables claramente definidos, procedimientos documentados, controles de acceso, mecanismos para atender los derechos de los titulares y evidencias que respalden el tratamiento de la información. Por ello, la protección de datos debe incorporarse como parte de la gestión organizacional y no limitarse a un requisito documental.
      p(data-aos="fade-left") Una adecuada gestión también reduce la improvisación, fortalece la coordinación entre las diferentes áreas y mejora la capacidad de respuesta frente a consultas, reclamaciones, auditorías e incidentes de seguridad. Los principales componentes de la gestión organizacional del tratamiento de datos se presentan a continuación:
      //- Slideshow
      .bg-full-width.bg-fondo-slider.mb-3
        .p-4.p-md-5
          SlyderA(tipo="b").bg-white.p-4.tarjeta(data-aos="fade-left")
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                 img(src='@/assets/curso/temas/t6/tarjeta05_1.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Roles internos
                p La organización debe definir responsabilidades para las áreas y personas que intervienen en el tratamiento de datos personales. Cada dependencia debe conocer sus funciones, los procedimientos que debe aplicar y la forma de atender las obligaciones relacionadas con la protección de la información.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t6/tarjeta05_2.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Procedimientos de control
                p Corresponden a los procesos documentados que regulan actividades como la recolección, actualización, consulta, almacenamiento, acceso, transferencia, supresión de datos, gestión de autorizaciones, atención de solicitudes y respuesta a incidentes de seguridad. Su aplicación permite estandarizar las actuaciones y reducir riesgos de incumplimiento.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t6/tarjeta05_3.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Documentación requerida
                p Comprende las políticas, procedimientos, registros y demás documentos que permiten demostrar el cumplimiento de la normativa. Esta documentación debe mantenerse actualizada, organizada y disponible para las áreas autorizadas y para las autoridades competentes cuando sea necesario.
      //- Fin Slideshow
      p(data-aos="fade-left") La gestión del tratamiento de datos requiere la participación coordinada de diferentes áreas de la organización. Los principales roles internos se presentan a continuación:
      //- Slideshow
      .bg-full-width.bg-fondo-slider.mb-3
        .p-4.p-md-5
          SlyderA(tipo="b").bg-white.p-4.tarjeta(data-aos="fade-left")
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                 img(src='@/assets/curso/temas/t6/tarjeta06_1.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Alta dirección
                p Aprobar las políticas institucionales, asignar recursos y respaldar el cumplimiento de la normativa.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t6/tarjeta06_2.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Área jurídica
                p Asesorar sobre los requisitos legales, revisar autorizaciones y apoyar la atención de consultas y reclamaciones.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t6/tarjeta06_3.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Tecnología
                p Implementar controles de seguridad, administrar accesos y proteger los sistemas de información.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t6/tarjeta06_4.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Talento humano
                p Gestionar y proteger los datos personales de trabajadores, candidatos y contratistas.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t6/tarjeta06_5.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Mercadeo
                p Utilizar bases de datos únicamente para las finalidades autorizadas.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t6/tarjeta06_6.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Servicio al cliente
                p Recibir y gestionar consultas, solicitudes y reclamaciones de los titulares.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t6/tarjeta06_7.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Archivo o gestión documental
                p Custodiar los soportes físicos y digitales relacionados con el tratamiento de datos.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t6/tarjeta06_8.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Coordinador de protección de datos
                p Coordinar los procedimientos, realizar seguimiento al cumplimiento y promover la mejora continua.
      //- Fin Slideshow
      .row.mb-5.justify-content-center.align-items-center        
        .col-12.col-sm-9.col-lg-5.order-1.order-lg-1.mb-4.mb-lg-0(data-aos="fade-right")
          figure.mb-0.text-center
            img.mx-auto(src='@/assets/curso/temas/t6/img12.png', alt='', style="width: 100%; max-width: 450px;")
        .col-12.col-lg-7.order-2.order-lg-2.bg-color-9.p-4(data-aos="fade-left")
          p.fw-bold.mb-2 Ejemplo
          p.mb-0 En una empresa comercial, el área de mercadeo desea desarrollar una campaña dirigida a antiguos clientes. Antes de utilizar la base de datos, verifica con el responsable de protección de datos que exista autorización para esa finalidad. Posteriormente, el área de tecnología garantiza la seguridad de la información y el servicio de atención al cliente dispone de los mecanismos necesarios para atender solicitudes de actualización, revocatoria o supresión.
      p(data-aos="fade-left") Los procedimientos de control permiten estandarizar el tratamiento de los datos personales y garantizar actuaciones uniformes en toda la organización.
      .row.bg-fondo-2(data-aos="fade-right")
        .col-12
          .pt-3.pb-5.px-5
            //- Inicio Tabla
            .row.justify-content-center.mb-5
              .col-md-auto.col-lg-10
                .titulo-sexto.color-acento-contenido.mb-3
                  h5 Tabla 9.
                  span Procedimientos para la gestión del tratamiento de datos personales y sus evidencias
                .tabla-a
                  table
                    thead
                      tr
                        th(style="width: 20%") Procedimiento
                        th(style="width: 40%") Propósito
                        th(style="width: 40%") Evidencia recomendada
                    tbody
                      tr
                        td Recolección de datos
                        td Garantizar la finalidad del tratamiento y la obtención de la autorización cuando corresponda.
                        td Formulario, aviso de privacidad y evidencia de la autorización.
                      tr
                        td Actualización de datos
                        td Mantener la información exacta y actualizada.
                        td Solicitud del titular y registro de la actualización realizada.
                      tr
                        td Atención de consultas y reclamaciones
                        td Garantizar el ejercicio de los derechos de los titulares.
                        td Radicado, respuesta y registro de seguimiento.
                      tr
                        td Control de accesos
                        td Restringir el acceso a la información al personal autorizado.
                        td Matriz de permisos y registros de acceso.
                      tr
                        td Gestión de proveedores
                        td Supervisar el tratamiento realizado por los encargados.
                        td Contratos, acuerdos de tratamiento y evaluaciones de seguridad.
                      tr
                        td Gestión de incidentes
                        td Atender oportunamente pérdidas, accesos no autorizados o vulneraciones de seguridad.
                        td Reportes de incidentes, análisis y acciones correctivas.
                      tr
                        td Supresión de datos
                        td Eliminar, bloquear o anonimizar la información cuando proceda.
                        td Acta, registro o evidencia del procedimiento realizado.
            //- FinTabla
      .row.mb-5.justify-content-center.align-items-center        
        .col-12.col-sm-9.col-lg-5.order-1.order-lg-1.mb-4.mb-lg-0(data-aos="fade-right")
          figure.mb-0.text-center
            img.mx-auto(src='@/assets/curso/temas/t6/img13.png', alt='', style="width: 100%; max-width: 500px;")
        .col-12.col-lg-7.order-2.order-lg-2.bg-color-4.p-4(data-aos="fade-left")
          p.mb-2.fw-bold Aplicación práctica
          p.mb-0 La documentación relacionada con el tratamiento de datos personales debe mantenerse organizada, actualizada y protegida mediante controles de acceso. Asimismo, es recomendable establecer responsables de su administración, fechas de revisión periódica y mecanismos de control de versiones que permitan asegurar que toda la organización utilice los documentos vigentes.

      
</template>

<script>
export default {
  name: 'Tema6',
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
