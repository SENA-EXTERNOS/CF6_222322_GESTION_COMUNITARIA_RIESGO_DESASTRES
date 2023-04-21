<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .row.justify-content-around.align-items-center.mb-5
      .col-lg-9.order-lg-1.order-2(data-aos="fade-right")
        p Apreciado aprendiz, bienvenido a este componente formativo, donde podrá apropiarse de los elementos, conceptos, acciones y metodologías para la asistencia en el proceso de verificación del cumplimiento de procedimientos, según protocolos de respuesta en situaciones de emergencia. Aprópiese de los elementos a través de los cuales se hace mantenimiento en seguridad, con base en el manual de operaciones y adquiera experticia en notificación de eventos, desde las alertas, alarmas y evaluación de daños.

        o.mb-0 En el siguiente video conocerá, de forma general, la temática que se estudiará a lo largo del componente formativo:


      .col-lg-2.col-4.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        img(src="@/assets/curso/intro/img01.svg")

    figure(data-aos="zoom-in")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/0W97mL8tJD8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)


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
