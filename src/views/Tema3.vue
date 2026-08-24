<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido
        .titulo-principal__numero
          span 3
        h1 Principios rectores para el tratamiento de datos
      .row.align-items-center.mb-4
        .col-12.col-lg-5.order-1.order-lg-1.mb-4.mb-lg-0(data-aos="fade-left")
          figure.mb-0
            img.mx-auto(src="@/assets/curso/temas/t3/img1.png", data-aos="zoom-in", style="width: 500px; width: 100%;")
        .col-12.col-lg-7.order-2.order-lg-2(data-aos="fade-right")
          p.p-3.bg-color-3.mb-3 Los principios rectores constituyen la base sobre la cual se desarrolla el sistema de protección de datos personales. Estos principios orientan las actuaciones de las organizaciones que recopilan, almacenan, utilizan, comparten o eliminan información personal, garantizando que el tratamiento de los datos se realice de manera responsable, transparente y respetuosa de los derechos de los titulares.
          p.p-3.bg-color-4.rounded-4.mb-0 Su aplicación permite establecer criterios claros para la gestión de la información y facilita el cumplimiento de las obligaciones legales relacionadas con la protección de datos personales. Su observancia es obligatoria para todos los responsables y encargados del tratamiento, independientemente del tamaño o la naturaleza de la organización. Más allá de su carácter jurídico, estos principios promueven una cultura organizacional basada en la confianza, la transparencia y el respeto por la privacidad de las personas.
      Separador
      //- Inicio Tema3.1
      .row
        #t_3_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
          h2 3.1 Principios relacionados con la legalidad 
      p(data-aos="fade-right") Los principios relacionados con la legalidad garantizan que el tratamiento de los datos personales se realice dentro del marco normativo vigente y con una finalidad claramente definida. Su aplicación evita prácticas arbitrarias o abusivas que puedan afectar los derechos de los titulares y exige que las organizaciones adopten procedimientos que permitan demostrar que la recolección y utilización de la información se desarrolla de forma legítima y conforme a la ley. Los principios relacionados con la legalidad se presentan a continuación:
      //- Pestanas horizontales
      .container.tarjeta.tarjeta--blanca.p-4.p-md-5(data-aos="fade-right")
        TabsC.color-acento-contenido.mt-1
          .py-3.py-md-4(titulo="Legalidad")
            .row.align-items-center 
              .col-md-6
                figure
                  img(src='@/assets/curso/temas/t3/tarjeta01_1.png')
              .col-md-6.mb-4.mb-md-0
                h4 Legalidad
                p El tratamiento de datos personales es una actividad reglada que debe sujetarse a las disposiciones legales vigentes. Ninguna organización puede recopilar, utilizar o compartir información personal sin fundamento legal. Este principio exige que las actividades relacionadas con el tratamiento de datos se desarrollen dentro de un marco jurídico que proteja los derechos de los titulares y que los procedimientos internos se encuentren documentados y alineados con la normativa aplicable.
          .py-3.py-md-4(titulo="Finalidad")
            .row.align-items-center
              .col-md-6.mb-4.mb-md-0
                figure
                  img(src='@/assets/curso/temas/t3/tarjeta01_2.png')
              .col-md-6
                h4 Finalidad
                p La recolección y el tratamiento de los datos personales deben responder a una finalidad legítima, específica y previamente informada al titular. La finalidad debe ser clara, verificable y coherente con las actividades de la organización. Los datos no pueden utilizarse para propósitos diferentes de aquellos para los cuales fueron recopilados, salvo que exista autorización del titular o una excepción prevista por la ley.              
          .py-3.py-md-4(titulo="Libertad")
            .row.align-items-center
              .col-md-6.mb-4.mb-md-0
                figure
                  img(src='@/assets/curso/temas/t3/tarjeta01_3.png')
              .col-md-6
                h4 Libertad
                p El tratamiento de los datos personales solo puede realizarse con el consentimiento previo, expreso e informado del titular. Este principio reconoce el derecho de las personas a decidir sobre el uso de su información y exige que la autorización pueda demostrarse mediante mecanismos que evidencien la aceptación voluntaria del titular. Asimismo, esta conserva el derecho de revocar la autorización cuando la normativa lo permita.              
      //- Cierres Pestanas horizontales
      p(data-aos="fade-right") Cada uno de estos principios orienta decisiones y actuaciones específicas dentro de las organizaciones, garantizando que el tratamiento de los datos personales se ajuste a los requisitos legales y respete los derechos de los titulares.
      .bloque-texto-g.bloque-texto-g--inverso.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5
        .bloque-texto-g__img(
          :style="{ backgroundImage: `url(${require_src('@/assets/curso/temas/t3/img3.png')})` }")
        .bloque-texto-g__texto.p-4
          p.mb-0 <b>Ejemplo:</b> 
            br
            br
            | Una empresa solicita información personal a sus clientes para registrar las garantías de sus productos. Antes de recopilar los datos, informa claramente la finalidad del tratamiento y obtiene la autorización correspondiente. De esta manera, actúa conforme a los principios de legalidad, finalidad y libertad establecidos en la Ley 1581 de 2012. Los principales aspectos que deben considerarse para garantizar el cumplimiento del principio de finalidad son los siguientes:
            ul.lista-ul.color-vinotinto-custom.mb-0
              li.d-flex.mt-3
                .fas.fa-check-circle.me-3
                span <b>Finalidad específica:</b> la información debe recopilarse para un propósito concreto y previamente definido.
            ul.lista-ul.color-vinotinto-custom.mb-0
              li.d-flex.mt-3
                .fas.fa-check-circle.me-3
                span <b>Información al titular:</b> la finalidad debe comunicarse de manera clara antes de realizar el tratamiento de los datos. 
            ul.lista-ul.color-vinotinto-custom.mb-0
              li.d-flex.mt-3
                .fas.fa-check-circle.me-3
                span <b>Relación con la actividad de la organización:</b> el tratamiento debe responder a las funciones y actividades propias de la organización. 
            ul.lista-ul.color-vinotinto-custom.mb-0
              li.d-flex.mt-3
                .fas.fa-check-circle.me-3
                span <b>Prohibición de cambios arbitrarios:</b> los datos no pueden utilizarse para finalidades diferentes sin la autorización correspondiente o sin respaldo legal. 
            ul.lista-ul.color-vinotinto-custom.mb-0
              li.d-flex.mt-3
                .fas.fa-check-circle.me-3
                span <b>Trazabilidad:</b> la organización debe conservar evidencia que permita demostrar la finalidad para la cual fueron recopilados los datos personales.
      .row.align-items-center.mb-4
        .col-12.col-lg-5.order-1.order-lg-1.mb-4.mb-lg-0(data-aos="fade-left")
          figure.mb-0
            img.mx-auto(src="@/assets/curso/temas/t3/img4.png", data-aos="zoom-in", style="width: 450px;")
        .col-12.col-lg-7.order-2.order-lg-2.p-3.bg-color-2(data-aos="fade-right")
          p.fw-bold Aplicación práctica
          p Cuando una organización implementa formularios físicos o digitales para recopilar datos personales, debe incorporar mecanismos que permitan obtener la autorización del titular, informar la finalidad del tratamiento y garantizar el cumplimiento de las disposiciones legales aplicables.

      Separador
      //- Inicio Tema3.2
      .row
        #t_3_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
          h2 3.2 Principios relacionados con la calidad de la información 
      .row.align-items-center.mb-4
        .col-12.col-lg-5.order-1.order-lg-2.mb-4.mb-lg-0(data-aos="fade-left")
          figure.mb-0
            img.mx-auto(src="@/assets/curso/temas/t3/img5.png", data-aos="zoom-in", style="width: 500px; width: 100%;")
        .col-12.col-lg-7.order-2.order-lg-1(data-aos="fade-right")
          p.p-3.bg-color-6.mb-3.rounded-4 La calidad de la información constituye un elemento esencial para garantizar un tratamiento adecuado de los datos personales. La información debe mantenerse exacta, verificable, comprensible, actualizada y accesible para los titulares cuando ejerzan sus derechos.
          p.p-3.bg-color-9.rounded-4.mb-0 La aplicación de estos principios permite que las organizaciones administren información confiable, reduzcan riesgos asociados con errores en los datos y garanticen que los titulares puedan conocer, actualizar o rectificar su información cuando sea necesario. Los principios relacionados con la calidad de la información se presentan a continuación:
      //- Pestanas horizontales
      .container.tarjeta.tarjeta--blanca.p-4.p-md-5(data-aos="fade-right")
        TabsC.color-acento-contenido.mt-1
          .py-3.py-md-4(titulo="Veracidad")
            .row.align-items-center                
              .col-md-6
                figure
                  img(src='@/assets/curso/temas/t3/tarjeta02_1.png')
              .col-md-6.mb-4.mb-md-0
                h4 Veracidad
                p La información sujeta a tratamiento debe ser veraz, completa, exacta, actualizada, comprobable y comprensible. Mantener datos de calidad permite evitar decisiones erróneas, proteger los derechos de los titulares y fortalecer la eficiencia de los procesos organizacionales. Por ello, las organizaciones deben establecer mecanismos que faciliten la actualización, verificación y corrección permanente de la información.
          .py-3.py-md-4(titulo="Transparencia")
            .row.align-items-center                
              .col-md-6.mb-4.mb-md-0
                figure
                  img(src='@/assets/curso/temas/t3/tarjeta02_2.png')
              .col-md-6
                h4 Transparencia
                p Garantiza el derecho de los titulares a conocer la existencia de sus datos personales y las condiciones bajo las cuales son tratados. Las organizaciones deben disponer de mecanismos que permitan consultar la información almacenada, identificar las finalidades del tratamiento y conocer quiénes tienen acceso a ella. Este principio fortalece la confianza y favorece el cumplimiento de las obligaciones legales relacionadas con el tratamiento de datos personales.              
          .py-3.py-md-4(titulo="Acceso y circulación restringida")
            .row.align-items-center                
              .col-md-6.mb-4.mb-md-0
                figure
                  img(src='@/assets/curso/temas/t3/tarjeta02_3.png')
              .col-md-6
                h4 Acceso y circulación restringida
                p Los datos personales solo pueden ser consultados por personas autorizadas y utilizados para las finalidades previamente informadas al titular. La información no debe encontrarse disponible para cualquier persona ni divulgarse indiscriminadamente. Su aplicación exige controles de acceso, mecanismos de autenticación y medidas de seguridad que protejan la confidencialidad de la información y reduzcan el riesgo de accesos no autorizados.
      //- Cierres Pestanas horizontales
      p(data-aos="fade-left") La aplicación conjunta de estos principios contribuye a garantizar la calidad de la información, fortalecer la confianza de los titulares y reducir los riesgos derivados del tratamiento inadecuado de los datos personales.
      .bloque-texto-g.bg-color-5.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-left")
        .bloque-texto-g__img(
          :style="{ backgroundImage: `url(${require_src('@/assets/curso/temas/t3/img6.png')})` }")
        .bloque-texto-g__texto.p-4
          p.mb-0 <b>Ejemplo: </b>
            br
            br
            | Una entidad financiera mantiene desactualizada la dirección de un cliente y envía comunicaciones a una ubicación incorrecta. Esta situación evidencia la importancia de verificar periódicamente la exactitud de la información y de implementar mecanismos que permitan mantener los datos actualizados durante todo su ciclo de vida. Los principales beneficios de garantizar la veracidad de la información son los siguientes:
            ul.lista-ul.color-vinotinto-custom.mb-0
              li.d-flex.mt-3
                .fas.fa-check-circle.me-3
                span <b>Mejora de la calidad de los procesos:</b> favorece la confiabilidad y consistencia de la información utilizada por la organización. 
              li.d-flex.mt-3
                .fas.fa-check-circle.me-3
                span <b>Reducción de errores administrativos:</b> disminuye inconsistencias, reprocesos y errores derivados de datos incorrectos o desactualizados. 
              li.d-flex.mt-3
                .fas.fa-check-circle.me-3
                span <b>Apoyo a la toma de decisiones:</b> facilita la adopción de decisiones fundamentadas en información precisa, completa y actualizada. 
              li.d-flex.mt-3
                .fas.fa-check-circle.me-3
                span <b>Fortalecimiento de la confianza de los titulares:</b> incrementa la credibilidad de la organización mediante un tratamiento responsable de los datos personales. 
              li.d-flex.mt-3
                .fas.fa-check-circle.me-3
                span <b>Disminución de riesgos operativos:</b> reduce la probabilidad de incidentes asociados al uso de información inexacta, incompleta o desactualizada.
      Separador
      //- Inicio Tema3.3
      .row
        #t_3_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
          h2 3.3 Principios relacionados con la protección de la información 
      .row.justify-content-center.align-items-stretch.mb-5
        .col-12.col-md-12.col-lg-5.mb-4.mb-lg-0(data-aos="fade-right")
          .bg-color-6.p-4.rounded-4.h-100.d-flex.align-items-center
            p.mb-0 La protección de los datos personales requiere la implementación de medidas que garanticen la confidencialidad, la integridad y la disponibilidad de la información durante todo su ciclo de vida. Estos principios orientan a las organizaciones en la adopción de controles que permitan prevenir incidentes de seguridad y proteger los derechos de los titulares.
        .col-12.col-md-12.col-lg-3.mb-4.mb-lg-0(data-aos="zoom-in")
          .h-100.d-flex
            img.rounded-3(src="@/assets/curso/temas/t3/img7.png", style="width: 100%; height: 100%; object-fit: cover;")
        .col-12.col-md-12.col-lg-4(data-aos="fade-left")
          .bg-color-7.p-4.rounded-4.h-100.d-flex.align-items-center
            p.mb-0 Su aplicación fortalece la gestión de la información, disminuye los riesgos asociados con el tratamiento de los datos personales y contribuye al cumplimiento de las obligaciones establecidas en la Ley 1581 de 2012. Los principios relacionados con la protección de la información se presentan a continuación:
      //- Slideshow
      .bg-full-width.bg-fondo-slider.mb-3
        .p-4.p-md-5
          SlyderA(tipo="b").bg-white.p-4.tarjeta(data-aos="fade-left")
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                 img(src='@/assets/curso/temas/t3/tarjeta03_1.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Seguridad
                p Las organizaciones deben adoptar medidas técnicas, humanas y administrativas que protejan los datos personales frente a riesgos de pérdida, alteración, acceso no autorizado, destrucción o uso fraudulento. La seguridad de la información no depende únicamente de herramientas tecnológicas; también comprende la capacitación del personal, la definición de procedimientos, la gestión de riesgos y la implementación de controles organizacionales que garanticen la protección de los datos durante todo su ciclo de vida.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t3/tarjeta03_2.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Confidencialidad
                p Todas las personas que intervienen en el tratamiento de datos personales tienen el deber de garantizar la reserva de la información, incluso después de finalizar su relación con la organización. Este principio impide que los datos sean divulgados o utilizados por personas no autorizadas y resulta especialmente relevante en sectores como salud, educación, servicios financieros y gestión del talento humano, donde se administra información sensible o de carácter reservado.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t3/tarjeta03_3.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 Aplicación de los principios
                p La protección efectiva de los datos personales requiere incorporar los principios rectores en las políticas, procedimientos y procesos institucionales. Cada actividad relacionada con la recolección, el almacenamiento, el uso, la circulación, la conservación y la supresión de la información debe desarrollarse conforme a los principios de legalidad, finalidad, libertad, veracidad, transparencia, acceso y circulación restringida, seguridad y confidencialidad. Su aplicación integral fortalece la protección de la información, reduce riesgos legales y operativos y consolida la confianza de los grupos de interés.
      p(data-aos="fade-left") La implementación de estos principios debe complementarse con medidas de seguridad acordes con la naturaleza de la información y con los riesgos identificados por cada organización. Las principales medidas para fortalecer la seguridad de la información son las siguientes:      
      //- Fin Slideshow
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
                          img(src='@/assets/curso/temas/t3/tarjeta04_1.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Contraseñas seguras
                            p.text-center Proteger el acceso a los sistemas de información mediante mecanismos de autenticación confiables.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t3/tarjeta04_2.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Control de accesos
                            p.text-center Limitar el acceso a la información únicamente al personal autorizado.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t3/tarjeta04_3.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Copias de respaldo
                            p.text-center Garantizar la recuperación de la información ante incidentes o pérdidas de datos.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t3/tarjeta04_4.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Cifrado de la información
                            p.text-center Proteger los datos durante su almacenamiento y transmisión.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t3/tarjeta04_5.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Monitoreo de sistemas
                            p.text-center Detectar oportunamente accesos no autorizados, incidentes y vulnerabilidades.
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t3/tarjeta04_6.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Capacitación del personal
                            p.text-center Fortalecer las competencias del personal para prevenir riesgos y aplicar buenas prácticas de seguridad.
                    .col-lg-4.order-lg-1.d-none.d-lg-block
                        figure
                          img(src='@/assets/curso/temas/t3/img8.png', style="width: 500px", data-aos="zoom-in").m-auto
              //- Fin Carrusel
      .row.justify-content-center.align-items-stretch.mb-3.g-0(data-aos="fade-right")
        .col-lg-7.bg-color-2.d-flex.flex-column.justify-content-center.p-4
          p.fw-bold.mb-2 Ejemplo:
          p.mb-3 Una entidad financiera mantiene desactualizada la dirección de un cliente y envía comunicaciones a una ubicación incorrecta. Esta situación evidencia la importancia de verificar periódicamente la exactitud de la información y de implementar mecanismos que permitan mantener los datos actualizados durante todo su ciclo de vida. Los principales beneficios de garantizar la veracidad de la información son los siguientes:
          ul.lista-ul.color-vinotinto-custom.mb-0
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Acuerdos de confidencialidad:</b> formalizar el compromiso de proteger la información personal a la que se tiene acceso durante el desarrollo de las funciones.
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Limitación de accesos según funciones:</b> garantizar que cada persona acceda únicamente a los datos necesarios para el cumplimiento de sus responsabilidades.
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Capacitación del personal:</b> fortalecer el conocimiento sobre las obligaciones, responsabilidades y buenas prácticas en materia de protección de datos personales.
            li.d-flex.mb-2
              i.fas.fa-check-circle.me-3
              span <b>Supervisión del uso de la información:</b> verificar el cumplimiento de las políticas de tratamiento de datos y detectar oportunamente posibles incumplimientos.
            li.d-flex.mb-0
              i.fas.fa-check-circle.me-3
              span <b>Aplicación de controles disciplinarios:</b> establecer medidas correctivas frente a conductas que comprometan la seguridad, la confidencialidad o el adecuado tratamiento de la información.
        .col-lg-5.d-flex
          figure.mb-0.w-100
            img.h-100.w-100(src='@/assets/curso/temas/t3/img9.png', alt='', style="object-fit: cover;")
      .row.justify-content-center.mb-4(data-aos="fade-left")
        .col-lg-12
          .d-flex.flex-column.flex-lg-row.align-items-center.bg-color-11.p-4.rounded-4
            .flex-shrink-0.mb-3.mb-lg-0.pe-lg-4
              img(src='@/assets/curso/temas/bg/icono-descargar-3.svg', style="width: 80px")
            .flex-grow-1.text-center.text-lg-start
              h4.mb-2.text-white Actividades de aplicación y análisis de los principios rectores para el tratamiento de datos personales
              p.mb-0.text-white Se invita a leer el documento <b>Actividades de aplicación y análisis de los principios rectores para el tratamiento de datos personales</b>, donde se aborda la aplicación práctica de los principios rectores establecidos en la Ley 1581 de 2012 mediante casos de análisis, ejemplos organizacionales y actividades de integración.
            .mt-3.mt-lg-0.ps-lg-4
              a.btn.btn-custom-download.w-buttons.d-flex.align-items-center.justify-content-center.p-3(:href="obtenerLink('/downloads/Anexos/Anexo_03_Actividades_Aplicación_Analisis.pdf')" target="_blank")
                span.fw-bold.me-2 Descargar
                i.fas.fa-file-download
</template>

<script>
export default {
  name: 'Tema3',
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
