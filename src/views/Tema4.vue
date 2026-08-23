<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido
        .titulo-principal__numero
          span 4
        h1 Categorías especiales de datos personales
      p(data-aos="fade-left") La protección de datos personales exige reconocer que no toda la información tiene el mismo nivel de sensibilidad, exposición o riesgo. Algunos datos pueden consultarse en fuentes públicas; otros requieren autorización para ser utilizados y algunos demandan medidas especiales de protección, debido a que pueden afectar la intimidad, la seguridad, la dignidad o los derechos fundamentales de una persona.
      .row.align-items-center.mb-5(data-aos="fade-right")
        .col-lg-8.order-2.order-lg-1
          .row.g-0.align-items-stretch.bg-color-3.mb-4
            .col-12.col-md-5.px-0
              img(src="@/assets/curso/temas/t4/img1.png", style="width:100%; height:100%; object-fit:cover;")
            .col-12.col-md-7.p-4.d-flex.align-items-center
              p.mb-0 La clasificación de los datos personales permite a las organizaciones identificar el tipo de información que administran, determinar el nivel de protección que requiere cada categoría y definir los controles necesarios para prevenir usos indebidos. Asimismo, facilita la asignación de responsabilidades, la gestión de permisos de acceso, la implementación de mecanismos de almacenamiento, la definición de tiempos de conservación y la atención de las solicitudes presentadas por los titulares.
          p.mb-0.bg-color-4.p-4 En el contexto organizacional, clasificar correctamente los datos constituye una actividad esencial para cumplir la normativa. No es equivalente tratar datos de contacto de un cliente que administrar historias clínicas, información financiera, datos biométricos o información de niños, niñas y adolescentes. Cada categoría requiere un tratamiento proporcional al nivel de riesgo que representa.
        .col-lg-4.order-1.order-lg-2.mb-4.mb-lg-0
          figure.mb-0
            img(src="@/assets/curso/temas/t4/img2.png", data-aos="zoom-in", style="width: 100%; max-width: 380px;").mx-auto
      p(data-aos="fade-left") Además, esta clasificación facilita la elaboración de políticas de tratamiento de datos personales, inventarios de bases de datos, matrices de riesgos y controles de seguridad. Por ello, antes de recopilar información, la organización debe identificar qué datos necesita, con qué finalidad los utilizará, quién podrá acceder a ellos y cuáles serán las medidas implementadas para garantizar su protección.            
      Separador
      //- Inicio Tema4.1
      .row
        #t_4_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
          h2 4.1 Clasificación de los datos personales 
      p(data-aos="fade-left") La clasificación de los datos personales consiste en organizar la información de acuerdo con su naturaleza, nivel de acceso, grado de sensibilidad y posible impacto sobre los derechos del titular. Este proceso permite diferenciar los datos que pueden consultarse públicamente de aquellos que requieren reserva o un nivel reforzado de protección.
      .row.justify-content-center.align-items-stretch.mb-5
        .col-12.col-md-12.col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
          .bg-color-2.p-4.rounded-4.h-100.d-flex.align-items-center
            p.mb-0 En las organizaciones, esta clasificación debe aplicarse desde el diseño de formularios, bases de datos, sistemas de información, procesos de selección, registros de clientes, expedientes laborales, historias clínicas, plataformas educativas y cualquier otro mecanismo mediante el cual se recopilen datos personales.
        .col-12.col-md-12.col-lg-4.mb-4.mb-lg-0(data-aos="zoom-in")
          .h-100.d-flex
            img.rounded-3(src="@/assets/curso/temas/t4/img3.png", style="width: 100%; height: 100%; object-fit: cover;")
        .col-12.col-md-12.col-lg-4(data-aos="fade-left")
          .bg-color-8.p-4.rounded-4.h-100.d-flex.align-items-center
            p.mb-0 Una adecuada clasificación evita tratar toda la información como si fuera pública o, por el contrario, aplicar restricciones innecesarias a datos que presentan un bajo nivel de riesgo. En consecuencia, las medidas de protección deben ser proporcionales a la naturaleza del dato y al riesgo asociado. Los principales tipos de datos personales se relacionan a continuación:
      //- Inicio Accordion
      .bg--img_03.mt-5
        .row.justify-content-center
          .col-lg-3.mb-5.mb-lg-0
            figure(data-aos="zoom-in")
              img(src="@/assets/curso/temas/t4/img4.png", alt="").img400.m-auto
          .col-lg-9
            AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta acordeonA")
              .row(titulo="Datos públicos")
                p.mb-4 Corresponden a información que no tiene carácter reservado y que puede ser conocida por terceros conforme a la ley. Aunque su acceso es permitido, su tratamiento debe respetar los principios de legalidad, finalidad, transparencia y seguridad.
                ul.lista-ul.color-naranja-custom.mb-0
                  li.d-flex.mb-2
                    i.fas.fa-arrow-circle-right.me-3
                    span
                      strong.d-block Ejemplo
                      span.d-block Estado civil, profesión u oficio, calidad de comerciante, información contenida en documentos públicos, registros mercantiles y demás fuentes públicas autorizadas.
                  li.d-flex.mb-2
                    i.fas.fa-arrow-circle-right.me-3
                    span
                      strong.d-block Medidas o consideraciones
                      span.d-block Deben #[u utilizarse]  únicamente para finalidades legítimas. Se recomienda documentar la fuente consultada, la finalidad del tratamiento y el responsable de la consulta.
              .row(titulo="Datos privados")
                p.mb-4 Son aquellos que solo interesan al titular o a un grupo limitado de personas autorizadas. Su divulgación puede afectar la privacidad, la seguridad, la situación económica o la vida laboral del titular.
                ul.lista-ul.color-naranja-custom.mb-0
                  li.d-flex.mb-2
                    i.fas.fa-arrow-circle-right.me-3
                    span
                      strong.d-block Ejemplo
                      span.d-block Información salarial, datos familiares, información financiera, información tributaria, evaluaciones de desempeño, expedientes laborales e información contractual.
                  li.d-flex.mb-2
                    i.fas.fa-arrow-circle-right.me-3
                    span
                      strong.d-block Medidas o consideraciones
                      span.d-block Requieren controles estrictos de acceso, almacenamiento seguro, políticas internas de protección y mecanismos que prevengan pérdidas, alteraciones o divulgaciones no autorizadas.
              .row(titulo="Datos semiprivados")
                p.mb-4 Son datos cuyo conocimiento puede interesar a un sector determinado o a personas autorizadas para una finalidad legítima. No pertenecen al ámbito íntimo del titular, pero tampoco son de libre consulta.
                ul.lista-ul.color-naranja-custom.mb-0
                  li.d-flex.mb-2
                    i.fas.fa-arrow-circle-right.me-3
                    span
                      strong.d-block Ejemplo
                      span.d-block Historial crediticio, comportamiento financiero, información comercial y comportamiento económico.
                  li.d-flex.mb-2
                    i.fas.fa-arrow-circle-right.me-3
                    span
                      strong.d-block Medidas o consideraciones
                      span.d-block Su consulta debe responder a una finalidad legítima y, cuando corresponda, contar con la autorización del titular o con habilitación legal. Es recomendable registrar las consultas realizadas y verificar la pertinencia del tratamiento.
      //- Fin Accordion
      p(data-aos="fade-left") La correcta clasificación de la información permite establecer controles diferenciados para cada categoría de datos personales y fortalece el cumplimiento de las obligaciones establecidas en la Ley 1581 de 2012.
      .bloque-texto-g.bloque-texto-g--inverso.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5
        .bloque-texto-g__img(
          :style="{ backgroundImage: `url(${require_src('@/assets/curso/temas/t4/img5.png')})` }")
        .bloque-texto-g__texto.p-4
          p.mb-0 <b>Ejemplo:</b> 
            br
            br
            | Una empresa consulta el registro mercantil de un proveedor antes de iniciar un proceso de contratación. La información corresponde a datos públicos y se utiliza para verificar la existencia legal del proveedor dentro de una finalidad legítima relacionada con el proceso contractual.
            br
            br
            | Por su parte, el área de talento humano administra hojas de vida, contratos, evaluaciones de desempeño, incapacidades y datos familiares de los trabajadores. Esta información corresponde a datos privados y debe conservarse con medidas de seguridad que limiten su consulta al personal autorizado.
            br
            br
            | De igual forma, una entidad financiera consulta el historial crediticio de una persona que solicita un préstamo. En este caso, la información corresponde a datos semiprivados y su tratamiento debe realizarse conforme a las condiciones legales aplicables y a la finalidad relacionada con la evaluación del riesgo crediticio.
      .row.mb-5.justify-content-center.align-items-center
          .col-12.col-sm-9.col-lg-5.order-1.order-lg-1.mb-4.mb-lg-0(data-aos="fade-left")
            figure.mb-0.text-center
              img(src='@/assets/curso/temas/t4/img6.png' style="width: 500px").m-auto
          .col-12.col-lg-7.order-2.order-lg-2.bg-color-9.p-4(data-aos="fade-right")
            p.fw-bold Aplicación práctica
            p Para gestionar adecuadamente las diferentes categorías de datos personales, las organizaciones pueden implementar procedimientos que permitan identificar el tipo de información recopilada, definir quién puede acceder a ella, establecer la finalidad del tratamiento y documentar las evidencias de las consultas realizadas. Estas acciones fortalecen el cumplimiento normativo y reducen los riesgos asociados con el tratamiento de la información.      
      Separador
      //- Inicio Tema4.2
      .row
        #t_4_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
          h2 4.2 Datos sensibles
      p(data-aos="fade-left") Los datos sensibles constituyen una categoría especial dentro de la protección de datos personales. Corresponden a información que puede afectar la intimidad del titular o cuyo uso indebido puede generar discriminación, exclusión, afectaciones laborales, daño moral, vulneración de la dignidad humana o riesgos para la seguridad personal.
      .row.mb-3.justify-content-center.align-items-center        
        .col-12.col-sm-9.col-lg-5.order-1.order-lg-1.mb-4.mb-lg-0(data-aos="fade-right")
          figure.mb-0.text-center
            img.mx-auto(src='@/assets/curso/temas/t4/img7.png', alt='', style="width: 100%; max-width: 500px;")
        .col-12.col-lg-7.order-2.order-lg-2.bg-color-3.p-4(data-aos="fade-left")
          p.mb-0 Debido a su naturaleza, estos datos requieren un nivel de protección superior al de las demás categorías de información. Su tratamiento solo puede realizarse cuando exista una finalidad legítima, una autorización válida o una de las excepciones previstas en la ley, además de medidas de seguridad acordes con el nivel de riesgo. En el contexto organizacional, los datos sensibles pueden estar presentes en procesos de seguridad y salud en el trabajo, historias clínicas, controles biométricos, programas de bienestar, investigaciones internas, procesos educativos y demás actividades que impliquen el tratamiento de información especialmente protegida.
      p(data-aos="fade-right") La adecuada gestión de estos datos exige aplicar controles específicos durante todo su ciclo de vida, ya que una falla en su tratamiento puede generar consecuencias para los titulares y responsabilidades legales para la organización. Los principales aspectos relacionados con el tratamiento de datos sensibles se presentan a continuación:          
      //- Slideshow
      .bg-full-width.bg-fondo-slider.mb-3
        .p-4.p-md-5
          SlyderA(tipo="b").bg-white.p-4.tarjeta(data-aos="fade-left")
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                 img(src='@/assets/curso/temas/t4/tarjeta01_1.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Concepto y características
                p Los datos sensibles corresponden a información relacionada con aspectos íntimos o especialmente protegidos de una persona, como el origen racial o étnico, la orientación política, las convicciones religiosas o filosóficas, la afiliación sindical, la información sobre salud, los datos biométricos y la información relativa a la vida sexual. Su tratamiento exige protección reforzada, autorización expresa, una finalidad específica, acceso restringido y la aplicación del principio de necesidad, evitando solicitar este tipo de información cuando no resulte indispensable para cumplir la finalidad prevista.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t4/tarjeta01_2.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Restricciones para su tratamiento
                p Como regla general, ninguna persona está obligada a suministrar datos sensibles. Antes de su recolección, la organización debe informar al titular que se trata de información especialmente protegida, explicar claramente la finalidad del tratamiento, indicar el carácter facultativo de la entrega de la información cuando corresponda y obtener una autorización expresa. Además, el acceso debe limitarse al personal autorizado y cualquier comunicación a terceros debe realizarse conforme a las condiciones establecidas por la ley.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t4/tarjeta01_3.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Medidas de protección
                p La protección de los datos sensibles requiere medidas técnicas, administrativas y organizacionales. Estas incluyen controles de acceso, cifrado de la información, autenticación multifactor, copias de respaldo, acuerdos de confidencialidad, capacitación del personal, definición de responsables, matrices de permisos, auditorías internas y protocolos para la atención de incidentes. La combinación de estas medidas fortalece la seguridad de la información y reduce la probabilidad de accesos no autorizados o divulgaciones indebidas.
      //- Fin Slideshow
      p(data-aos="fade-left") Las principales características de los datos sensibles se relacionan a continuación:
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
                              img(src='@/assets/curso/temas/t4/tarjeta02_1.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Protección reforzada
                            p.text-center Requieren medidas de seguridad más estrictas que las aplicadas a otros datos personales.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t4/tarjeta02_2.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Riesgo de discriminación
                            p.text-center Su uso indebido puede afectar la igualdad, la dignidad y otros derechos fundamentales del titular.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t4/tarjeta02_3.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Autorización expresa
                            p.text-center El titular debe aceptar de manera libre, previa, expresa e informada el tratamiento de la información, salvo las excepciones legales.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t4/tarjeta02_4.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Finalidad específica
                            p.text-center Solo pueden recopilarse cuando exista una necesidad legítima y claramente definida.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t4/tarjeta02_5.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold Acceso restringido
                            p.text-center Deben ser consultados únicamente por personas autorizadas para el cumplimiento de sus funciones.
                    .col-lg-4.order-lg-1.d-none.d-lg-block
                        figure
                          img(src='@/assets/curso/temas/t4/img8.png', style="width: 500px", data-aos="zoom-in").m-auto
              //- Fin Carrusel
      .bloque-texto-g.bloque-texto-g--inverso.color-secundario.p-3.p-sm-4.p-md-5.mb-5
        .bloque-texto-g__img(
          :style="{ backgroundImage: `url(${require_src('@/assets/curso/temas/t4/img9.png')})` }")
        .bloque-texto-g__texto.p-4
          p.mb-0 <b>Ejemplo</b>
            br
            br
            | Una clínica administra historias clínicas que contienen diagnósticos, tratamientos, antecedentes médicos y resultados de exámenes. Debido a la naturaleza de esta información, debe implementar controles reforzados que garanticen la confidencialidad, la integridad y la disponibilidad de los datos.
            br
            br
            | Otro ejemplo corresponde a una empresa que utiliza la huella dactilar para controlar el ingreso de sus trabajadores. Al tratarse de un dato biométrico, la organización debe justificar su utilización, obtener la autorización correspondiente e implementar medidas técnicas y administrativas que garanticen su protección.      
      .row.justify-content-center.align-items-stretch.mb-3.g-0(data-aos="fade-right")
        .col-lg-5.d-flex
          figure.mb-0.w-100
            img.h-100.w-100(src='@/assets/curso/temas/t4/img10.png', alt='', style="object-fit: cover;")
        .col-lg-7.bg-color-2.d-flex.flex-column.justify-content-center.p-4
          p.mb-2 Los principales requisitos para el tratamiento de datos sensibles son los siguientes:
          ul.lista-ul.color-vinotinto-custom.mb-0
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Informar la naturaleza sensible del dato:</b> comunicar al titular que la información corresponde a un dato sensible y requiere un nivel especial de protección.
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Explicar la finalidad:</b> informar de manera clara para qué se solicita la información y cómo será utilizada durante su tratamiento.
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Obtener autorización expresa:</b> conservar evidencia de la autorización libre, previa, expresa e informada del titular, cuando la normativa lo exija.
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Limitar la recolección:</b> solicitar únicamente los datos sensibles que sean estrictamente necesarios para cumplir la finalidad prevista.
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Proteger el acceso:</b> restringir el acceso a la información sensible exclusivamente al personal autorizado mediante controles de seguridad adecuados.
      .row.mb-5.justify-content-center.align-items-center        
        .col-12.col-sm-9.col-lg-5.order-1.order-lg-2.mb-4.mb-lg-0(data-aos="fade-right")
          figure.mb-0.text-center
            img.mx-auto(src='@/assets/curso/temas/t4/img11.png', alt='', style="width: 100%; max-width: 500px;")
        .col-12.col-lg-7.order-2.order-lg-1.bg-color-10.p-3(data-aos="fade-left")
          p.mb-3.fw-bold Ejemplo organizacional
          p Una empresa solicita información sobre las condiciones médicas de sus trabajadores para desarrollar actividades de seguridad y salud en el trabajo. Antes de recopilar esta información, informa la finalidad del tratamiento, limita el acceso al personal competente y adopta medidas de seguridad para proteger los documentos físicos y digitales donde se almacena la información. Las principales medidas para fortalecer la protección de los datos sensibles se presentan a continuación:
      .row.bg-fondo-2(data-aos="fade-right")
        .col-12
          .pt-3.pb-5.px-5
            //- Inicio Tabla
            .row.justify-content-center.mb-5
              .col-md-auto.col-lg-10
                .titulo-sexto.color-acento-contenido.mb-3
                  h5 Tabla 2.
                  span Medidas de protección para el tratamiento seguro de datos personales sensibles
                .tabla-a
                  table
                    thead
                      tr
                        th(style="width: 20%") Tipo de medida
                        th(style="width: 30%") Ejemplo
                        th(style="width: 60%") Propósito
                    tbody
                      tr
                        td Técnica
                        td Cifrado de bases de datos.
                        td Proteger la información frente a accesos no autorizados.
                      tr
                        td Administrativa
                        td Acuerdos de confidencialidad.
                        td Fortalecer el compromiso del personal con la reserva de la información.
                      tr
                        td Organizacional
                        td Matriz de permisos.
                        td Definir quién puede consultar, modificar o administrar los datos sensibles.
                      tr
                        td Preventiva
                        td Capacitación al personal.
                        td Reducir errores humanos durante el tratamiento de la información.
                      tr
                        td Correctiva
                        td Protocolo para la atención de incidentes.
                        td Responder oportunamente ante vulneraciones de seguridad.
            //- FinTabla
            Separador
            //- Inicio Tema4.3
            .row
              #t_4_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
                h2 4.3 Datos de niños, niñas y adolescentes
      p(data-aos="fade-left") Los datos personales de niños, niñas y adolescentes cuentan con una protección especial, debido a que sus titulares se encuentran en una condición que exige mayores garantías para la protección de sus derechos. En consecuencia, cualquier tratamiento de esta información debe orientarse por el principio del interés superior del menor y por el respeto de sus derechos fundamentales.
      .row.align-items-center.mb-5(data-aos="fade-right")
        .col-lg-8.order-2.order-lg-1
          .row.g-0.align-items-stretch.bg-color-2.mb-4
            .col-12.col-md-5.px-0
              img(src="@/assets/curso/temas/t4/img12.png", style="width:100%; height:100%; object-fit:cover;")
            .col-12.col-md-7.p-4.d-flex.align-items-center
              p.mb-0 Las organizaciones que administran información de menores de edad, como instituciones educativas, entidades deportivas, fundaciones, plataformas tecnológicas, programas sociales, entidades de salud y organizaciones recreativas, deben actuar con especial diligencia durante la recolección, el uso, el almacenamiento, la circulación y la eliminación de estos datos.
          p.mb-0.bg-color-8.p-4 El tratamiento de esta información no debe limitarse al cumplimiento de requisitos administrativos. También debe considerar los riesgos derivados de la posible exposición de fotografías, información académica, datos familiares, información médica, datos de ubicación o cualquier otro dato que pueda comprometer la seguridad, la intimidad o el desarrollo integral del menor.
        .col-lg-4.order-1.order-lg-2.mb-4.mb-lg-0
          figure.mb-0
            img(src="@/assets/curso/temas/t4/img14.png", data-aos="zoom-in", style="width: 100%; max-width: 350px;").mx-auto
      p(data-aos="fade-left") Por esta razón, las organizaciones deben establecer procedimientos específicos para garantizar un tratamiento seguro, proporcional y conforme con la normativa vigente. Los principales aspectos relacionados con el tratamiento de datos personales de niños, niñas y adolescentes se presentan a continuación:
      //- Inicio Accordion
      .bg--img_03.mt-5
        .row.justify-content-center
          .col-lg-3.mb-5.mb-lg-0
            figure(data-aos="zoom-in")
              img(src="@/assets/curso/temas/t4/img4.png", alt="").img400.m-auto
          .col-lg-9
            AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta acordeonA")
              .row(titulo="Protección especial")
                p.mb-4 La protección de los datos personales de niños, niñas y adolescentes tiene como finalidad garantizar su desarrollo integral, su dignidad, su seguridad y el ejercicio pleno de sus derechos. Toda decisión relacionada con el tratamiento de esta información debe responder al principio del interés superior del menor, evitando cualquier uso que pueda generar exposición, discriminación, afectaciones a la intimidad o riesgos para su integridad.                
              .row(titulo="Requisitos para el tratamiento")
                p.mb-4 El tratamiento debe responder a una finalidad legítima y necesaria, contar con la autorización del representante legal cuando sea exigible, aplicar medidas de seguridad apropiadas y limitar la recolección únicamente a los datos indispensables para cumplir la finalidad prevista. Además, la organización debe garantizar que la información permanezca protegida durante todo su ciclo de vida.
              .row(titulo="Casos de aplicación")
                p.mb-4 Los datos de niños, niñas y adolescentes se tratan en diferentes contextos, como instituciones educativas, escuelas deportivas, plataformas digitales y programas sociales. En todos los casos, la organización debe evaluar el tipo de información tratada, los riesgos asociados, los permisos de acceso, las autorizaciones obtenidas y las medidas de protección implementadas para garantizar el respeto de los derechos de los menores.
      //- Fin Accordion
      p(data-aos="fade-left") Las principales situaciones que requieren una protección especial se relacionan a continuación:
      .row.bg-fondo-2(data-aos="fade-right")
        .col-12
          .pt-3.pb-5.px-5
            //- Inicio Tabla
            .row.justify-content-center.mb-5
              .col-md-auto.col-lg-10
                .titulo-sexto.color-acento-contenido.mb-3
                  h5 Tabla 3.
                  span  Riesgos y medidas de protección en el tratamiento de datos personales en el ámbito educativo
                .tabla-a
                  table
                    thead
                      tr
                        th(style="width: 20%") Situación
                        th(style="width: 30%") Riesgo principal
                        th(style="width: 50%") Medida recomendada
                    tbody
                      tr
                        td Publicación de fotografías de menores.
                        td Uso no autorizado de la imagen.
                        td Obtener autorización previa y definir claramente la finalidad del tratamiento.
                      tr
                        td Compartir listados de estudiantes.
                        td Exposición de datos personales.
                        td Restringir el acceso y utilizar canales institucionales seguros.
                      tr
                        td Almacenamiento de datos médicos escolares.
                        td Divulgación de datos sensibles.
                        td Aplicar medidas de protección reforzada y limitar el acceso al personal autorizado.
                      tr
                        td Uso de plataformas educativas.
                        td Acceso no autorizado a la información.
                        td Configurar adecuadamente los permisos de acceso y administrar los usuarios de forma segura.
            //- FinTabla
      .row.mb-5.justify-content-center.align-items-center        
        .col-12.col-sm-9.col-lg-5.order-1.order-lg-1.mb-4.mb-lg-0(data-aos="fade-right")
          figure.mb-0.text-center
            img.mx-auto(src='@/assets/curso/temas/t4/img15.png', alt='', style="width: 600px;")
        .col-12.col-lg-7.order-2.order-lg-2.bg-color-9.p-2(data-aos="fade-left")
          p.mb-3.fw-bold Ejemplo
          p Una institución educativa toma fotografías durante una actividad académica y desea publicarlas en sus medios institucionales. Antes de hacerlo, debe verificar que cuenta con la autorización correspondiente, que existe una finalidad legítima para el tratamiento y que la publicación no expone innecesariamente a los estudiantes. Los principales requisitos para el tratamiento de datos personales de menores de edad son los siguientes:
          ul.lista-ul.color-vinotinto-custom.mb-0
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Finalidad legítima:</b> verificar que la información del menor se recopile para un propósito específico, legítimo y relacionado con las actividades de la organización.
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Necesidad:</b> confirmar que los datos solicitados sean indispensables para cumplir la finalidad prevista.
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Autorización:</b> verificar que se cuente con la autorización válida del representante legal, cuando sea exigible.
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Seguridad:</b> garantizar que la información se almacene, consulte y proteja mediante controles de seguridad adecuados.
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Proporcionalidad:</b> asegurar que únicamente se recopilen los datos personales estrictamente necesarios para la finalidad definida.
      //- Título nivel 3 - Imagen
      .titulo-tercer-nivel.mb-5.mt-3(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/temas/bg/titulos.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 Aplicación práctica
      //- Título nivel 3 - Imagen
      p(data-aos="fade-left") Al revisar un formulario de inscripción dirigido a menores de edad, la organización debe verificar que cada dato solicitado tenga una finalidad claramente justificada. Cuando un dato no resulte necesario para la prestación del servicio o el desarrollo de la actividad, debe eliminarse del formulario o justificarse técnicamente su necesidad. Los principales entornos en los que se realiza el tratamiento de datos personales de niños, niñas y adolescentes son los siguientes:
      .row.bg-fondo-2(data-aos="fade-right")
        .col-12
          .pt-3.pb-5.px-5
            //- Inicio Tabla
            .row.justify-content-center.mb-5
              .col-md-auto.col-lg-10
                .titulo-sexto.color-acento-contenido.mb-3
                  h5 Tabla 3.
                  span  Riesgos y medidas de protección en el tratamiento de datos personales en el ámbito educativo
                .tabla-a
                  table
                    thead
                      tr
                        th(style="width: 10%") Situación
                        th(style="width: 30%") Datos tratados
                        th(style="width: 30%") Riesgo principal
                        th(style="width: 30%") Control recomendado
                    tbody
                      tr
                        td Institución educativa
                        td Calificaciones, asistencia y datos familiares.
                        td Exposición de información académica o familiar.
                        td Acceso por roles y utilización de canales institucionales.
                      tr
                        td Escuela deportiva
                        td Datos de salud, acudientes y fotografías.
                        td Uso indebido de la imagen o de la información médica.
                        td Autorizaciones previas y almacenamiento seguro.
                      tr
                        td Plataforma digital
                        td Usuario, correo electrónico y actividad en línea.
                        td Acceso no autorizado o exposición digital.
                        td Configuración de privacidad, autenticación y monitoreo.
                      tr
                        td Programa social
                        td Caracterización familiar y datos de contacto.
                        td Divulgación indebida o estigmatización.
                        td Reserva documental y tratamiento conforme a la finalidad declarada.
      .row.justify-content-center.mb-4(data-aos="fade-left")
        .col-lg-12
          .d-flex.flex-column.flex-lg-row.align-items-center.bg-color-11.p-4.rounded-4
            .flex-shrink-0.mb-3.mb-lg-0.pe-lg-4
              img(src='@/assets/curso/temas/bg/icono-descargar-4.svg', style="width: 80px")
            .flex-grow-1.text-center.text-lg-start
              h4.mb-2.text-white Actividades de aplicación y análisis de las categorías especiales de datos personales[
              p.mb-0.text-white Se invita a leer el documento<b> Actividades de aplicación y análisis de las categorías especiales de datos personales</b>, donde se aborda la clasificación de los datos personales, el tratamiento de datos sensibles y de niños, niñas y adolescentes, así como las medidas de protección exigidas por la Ley 1581 de 2012.
            .mt-3.mt-lg-0.ps-lg-4
              a.btn.btn-custom-download.w-buttons.d-flex.align-items-center.justify-content-center.p-3(:href="obtenerLink('/downloads/Lectura-Programas-técnicos-para-la-prevención-sanitaria.docx')" target="_blank")
                span.fw-bold.me-2 Descargar
                i.fas.fa-file-download

</template>

<script>
export default {
  name: 'Tema4',
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
