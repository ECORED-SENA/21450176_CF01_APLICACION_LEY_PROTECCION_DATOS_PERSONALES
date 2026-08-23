<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido
        .titulo-principal__numero
          span 7
        h1 Vigilancia, control y sanciones
      p.mb-4(data-aos="fade-left") XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
      .row.align-items-center.mb-5(data-aos="fade-right")
        .col-lg-8.order-2.order-lg-1
          .row.g-0.align-items-stretch.bg-color-2.mb-4
            .col-12.col-md-5.px-0
              img(src="@/assets/curso/temas/intro/img1.png", style="width:100%; height:100%; object-fit:cover;")
            .col-12.col-md-7.p-4.d-flex.align-items-center
              p.mb-0 XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
          p.mb-0 XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
        .col-lg-4.order-1.order-lg-2.mb-4.mb-lg-0
          figure.mb-0
            img(src="@/assets/curso/temas/intro/img2.png", data-aos="zoom-in", style="width: 100%; max-width: 380px;").mx-auto
      Separador
      //- Inicio Tema7.1
      .row
        #t_7_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
          h2 7.1 Autoridades de control
      .row.align-items-center.mb-4
        .col-12.col-lg-5.order-1.order-lg-2.mb-4.mb-lg-0(data-aos="fade-left")
          figure.mb-0
            img.mx-auto(src="@/assets/curso/temas/t1/img1.png", data-aos="zoom-in", style="width: 500px; width: 100%;")
        .col-12.col-lg-7.order-2.order-lg-1(data-aos="fade-right")
          p.p-3.bg-color-3.mb-3 XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
          p.p-3.bg-color-4.rounded-4.mb-0 YYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYY
      //- Slideshow
      .bg-full-width.bg-fondo-slider.mb-3
        .p-4.p-md-5
          SlyderA(tipo="b").bg-white.p-4.tarjeta(data-aos="fade-left")
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                 img(src='@/assets/curso/temas/t1/tarjeta03_1.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 XXXXXXXXXXXXXXXXXXXXXX
                p XXXXXXXXXXXXXXXXXXXXXXXXXX
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t1/tarjeta03_2.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 XXXXXXXXXXXXXXXXXXXXXX
                p XXXXXXXXXXXXXXXXXXXXXXXXXX
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src='@/assets/curso/temas/t1/tarjeta03_3.png')
              .col-lg-7.order-1.mb-3.mb-lg-0
                h4 XXXXXXXXXXXXXXXXXXXXXX
                p XXXXXXXXXXXXXXXXXXXXXXXXXX
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
                          img(src='@/assets/curso/temas/t1/tarjeta02_1.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Afecta
                            p xxxxxxxxx
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t1/tarjeta02_2.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Afecta
                            p xxxxxxxxx
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t1/tarjeta02_3.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Afecta
                            p xxxxxxxxx
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t1/tarjeta02_4.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Afecta
                            p xxxxxxxxx
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t1/tarjeta02_5.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Afecta
                            p xxxxxxxxx
                    .col-lg-4.order-lg-1.d-none.d-lg-block
                        figure
                          img(src='@/assets/curso/temas/t1/img6.png', style="width: 500px", data-aos="zoom-in").m-auto
              //- Fin Carrusel
      .bloque-texto-g.bloque-texto-g--inverso.color-secundario.p-3.p-sm-4.p-md-5
        .bloque-texto-g__img(
          :style="{ backgroundImage: `url(${require_src('@/assets/curso/temas/intro/img1.png')})` }")
        .bloque-texto-g__texto.p-4
          p.mb-0 XXXXXXXXXXXXXXXXXXXXX
            br
            | XXXXXXXXXXXXXXXXXXXXXXXXXXXXX





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
                            h4.card-title.text-center.mb-3.fw-bold XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                            p.text-start XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t1/tarjeta01_2.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                            p.text-start XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t1/tarjeta01_3.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                            p.text-start XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t1/tarjeta01_4.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                            p.text-start XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t1/tarjeta01_5.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                            p.text-start XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                    .col-lg-4.order-lg-1.d-none.d-lg-block
                        figure
                          img(src='@/assets/curso/temas/t1/img2.png', style="width: 500px", data-aos="zoom-in").m-auto
              //- Fin Carrusel              
      Separador
      //- Inicio Tema7.2
      .row
        #t_7_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
          h2 7.2 Régimen sancionatorio
      .row.justify-content-center.align-items-stretch
        .col-12.col-md-12.col-lg-5.mb-4.mb-lg-0(data-aos="fade-right")
          .bg-color-6.p-4.rounded-4.h-100.d-flex.align-items-center
            p.mb-0 La protección de los datos personales requiere la implementación de medidas que garanticen la confidencialidad, la integridad y la disponibilidad de la información durante todo su ciclo de vida. Estos principios orientan a las organizaciones en la adopción de controles que permitan prevenir incidentes de seguridad y proteger los derechos de los titulares.
        .col-12.col-md-12.col-lg-3.mb-4.mb-lg-0(data-aos="zoom-in")
          .h-100.d-flex
            img.rounded-3(src="@/assets/curso/temas/t3/img7.png", style="width: 100%; height: 100%; object-fit: cover;")
        .col-12.col-md-12.col-lg-4(data-aos="fade-left")
          .bg-color-7.p-4.rounded-4.h-100.d-flex.align-items-center
            p.mb-0 Su aplicación fortalece la gestión de la información, disminuye los riesgos asociados con el tratamiento de los datos personales y contribuye al cumplimiento de las obligaciones establecidas en la Ley 1581 de 2012. Los principios relacionados con la protección de la información se presentan a continuación:

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
                            h4.card-title.text-center.mb-3 Afecta
                            p xxxxxxxxx
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t1/tarjeta02_2.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Afecta
                            p xxxxxxxxx
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t1/tarjeta02_3.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Afecta
                            p xxxxxxxxx
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t1/tarjeta02_4.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Afecta
                            p xxxxxxxxx
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden
                          img(src='@/assets/curso/temas/t1/tarjeta02_5.png').w-100
                          .p-4
                            h4.card-title.text-center.mb-3 Afecta
                            p xxxxxxxxx
                    .col-lg-4.order-lg-1.d-none.d-lg-block
                        figure
                          img(src='@/assets/curso/temas/t1/img6.png', style="width: 500px", data-aos="zoom-in").m-auto
              //- Fin Carrusel
      .row.bg-fondo-2(data-aos="fade-right")
        .col-12
          .pt-3.pb-5.px-5
            //- Inicio Tabla
            .row.justify-content-center.mb-5
              .col-md-auto
                .titulo-sexto.color-acento-contenido.mb-3
                  h5 Tabla 1.
                  span  xxxxxxxx
                .tabla-a
                  table
                    thead
                      tr
                        th(style="width: 40%") xxxxxxx
                        th(style="width: 60%") xxxxxxxx
                    tbody
                      tr
                        td xxxxxxxx
                        td xxxxxxxx
                      tr
                        td xxxxxxxx
                        td xxxxxxxx
                      tr
                        td xxxxxxxx
                        td xxxxxxxx
                      tr
                        td xxxxxxxx
                        td xxxxxxxx
                      tr
                        td xxxxxxxx
                        td xxxxxxxx
            //- FinTabla

      Separador
      //- Inicio Tema7.3
      .row
        #t_7_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
          h2 7.3 Gestión del riesgo legal 
      .row.align-items-center.mb-4
        .col-12.col-lg-5.order-1.order-lg-2.mb-4.mb-lg-0(data-aos="fade-left")
          figure.mb-0
            img.mx-auto(src="@/assets/curso/temas/t1/img1.png", data-aos="zoom-in", style="width: 500px; width: 100%;")
        .col-12.col-lg-7.order-2.order-lg-1(data-aos="fade-right")
          p.p-3.bg-color-3.mb-3 XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
          p.p-3.bg-color-4.rounded-4.mb-0 YYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYY          

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
              .row(titulo="Datos privados")
                p.mb-4 Son aquellos que solo interesan al titular o a un grupo limitado de personas autorizadas. Su divulgación puede afectar la privacidad, la seguridad, la situación económica o la vida laboral del titular.
              .row(titulo="Datos semiprivados")
                p.mb-4 Son datos cuyo conocimiento puede interesar a un sector determinado o a personas autorizadas para una finalidad legítima. No pertenecen al ámbito íntimo del titular, pero tampoco son de libre consulta.
      //- Fin Accordion      
      
      .row.bg-fondo-2(data-aos="fade-right")
        .col-12
          .pt-3.pb-5.px-5
            //- Inicio Tabla
            .row.justify-content-center.mb-5
              .col-md-auto
                .titulo-sexto.color-acento-contenido.mb-3
                  h5 Tabla 1.
                  span  xxxxxxxx
                .tabla-a
                  table
                    thead
                      tr
                        th(style="width: 40%") xxxxxxx
                        th(style="width: 60%") xxxxxxxx
                    tbody
                      tr
                        td xxxxxxxx
                        td xxxxxxxx
                      tr
                        td xxxxxxxx
                        td xxxxxxxx
                      tr
                        td xxxxxxxx
                        td xxxxxxxx
                      tr
                        td xxxxxxxx
                        td xxxxxxxx
                      tr
                        td xxxxxxxx
                        td xxxxxxxx
            //- FinTabla
      //- Título nivel 3 - Imagen
      .titulo-tercer-nivel.mb-5.mt-3(data-aos="fade-right")
        img.titulo-tercer-nivel__icon(src='@/assets/curso/temas/bg/titulos.svg')
        h3.titulo-tercer-nivel__text.mb-0.px-0.py-2 Clasificación según la aptitud productiva
      //- Título nivel 3 - Imagen

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
                            h4.card-title.text-center.mb-3.fw-bold XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                            p.text-start XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t1/tarjeta01_2.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                            p.text-start XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t1/tarjeta01_3.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                            p.text-start XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t1/tarjeta01_4.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                            p.text-start XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t1/tarjeta01_5.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                            p.text-start XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                    .col-lg-4.order-lg-1.d-none.d-lg-block
                        figure
                          img(src='@/assets/curso/temas/t1/img2.png', style="width: 500px", data-aos="zoom-in").m-auto
              //- Fin Carrusel

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
                            h4.card-title.text-center.mb-3.fw-bold XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                            p.text-start XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t1/tarjeta01_2.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                            p.text-start XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t1/tarjeta01_3.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                            p.text-start XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t1/tarjeta01_4.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                            p.text-start XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                        .bg-white.tarjeta.h-100.shadow-app.bordes.overflow-hidden.p-4.text-center
                          .row.justify-content-center.mb-3.mt-3
                            .col-auto
                              img(src='@/assets/curso/temas/t1/tarjeta01_5.svg' alt='' style="width: 90px; height: 90px; object-fit: contain;").mx-auto
                          .p-2
                            h4.card-title.text-center.mb-3.fw-bold XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                            p.text-start XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                    .col-lg-4.order-lg-1.d-none.d-lg-block
                        figure
                          img(src='@/assets/curso/temas/t1/img2.png', style="width: 500px", data-aos="zoom-in").m-auto
              //- Fin Carrusel
      .row.justify-content-center.mb-4(data-aos="fade-left")
        .col-lg-12
          .d-flex.flex-column.flex-lg-row.align-items-center.bg-color-11.p-4.rounded-4
            .flex-shrink-0.mb-3.mb-lg-0.pe-lg-4
              img(src='@/assets/curso/temas/bg/icono-descargar.svg', style="width: 80px")
            .flex-grow-1.text-center.text-lg-start
              h4.mb-2.text-white XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
              p.mb-0.text-white ZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZ
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
              h4.mb-2.text-white XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
              p.mb-0.text-white ZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZ
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
