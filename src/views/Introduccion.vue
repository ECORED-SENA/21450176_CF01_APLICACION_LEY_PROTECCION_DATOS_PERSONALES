<template lang="pug">
  .curso-main-container.introduccion
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido
        .titulo-principal__numero
          span
            i.fas.fa-info
        h1 Introducción
      p.mb-4(data-aos="fade-left") En la actualidad, la información personal constituye uno de los activos más valiosos para las personas, las organizaciones y la sociedad. El uso creciente de tecnologías digitales, plataformas en línea, aplicaciones móviles y sistemas de información ha incrementado la recolección, el almacenamiento y el intercambio de datos personales, haciendo indispensable la adopción de medidas que garanticen su tratamiento adecuado. En este contexto, la protección de los datos personales representa un elemento esencial para salvaguardar derechos fundamentales como la intimidad, la privacidad, el buen nombre y el habeas data.
      .row.align-items-center.mb-5(data-aos="fade-right")
        .col-lg-8.order-2.order-lg-1
          .row.g-0.align-items-stretch.bg-color-2.mb-4
            .col-12.col-md-5.px-0
              img(src="@/assets/curso/temas/intro/img1.png", style="width:100%; height:100%; object-fit:cover;")
            .col-12.col-md-7.p-4.d-flex.align-items-center
              p.mb-0 Este componente formativo presenta los fundamentos de la protección de datos personales en Colombia, con énfasis en las disposiciones establecidas por la Ley 1581 de 2012 y su marco regulatorio. A lo largo del contenido se analizan los principios rectores, los derechos de los titulares, las responsabilidades de quienes intervienen en el tratamiento de la información, las categorías especiales de datos personales, las medidas de seguridad y los mecanismos que permiten garantizar el cumplimiento de la normativa vigente.          
          p.mb-0 Asimismo, se promueve la aplicación práctica de estos conocimientos mediante el análisis de situaciones organizacionales que permiten identificar riesgos, adoptar medidas preventivas y fortalecer la gestión responsable de la información. De esta manera, el componente busca desarrollar las competencias necesarias para implementar buenas prácticas de protección de datos personales, contribuir al cumplimiento legal y fomentar una cultura organizacional basada en la transparencia, la seguridad de la información y el respeto por los derechos de los titulares.
        .col-lg-4.order-1.order-lg-2.mb-4.mb-lg-0
          figure.mb-0
            img(src="@/assets/curso/temas/intro/img2.png", data-aos="zoom-in", style="width: 100%; max-width: 380px;").mx-auto
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
