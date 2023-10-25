<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .row.justify-content-center.mb-5
      .col-lg-5.col-10.mb-lg-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/intro/img01.svg' alt="Imagen decorativa")
      .col-lg-7
        p.mb-xl-5(data-aos="fade-left") Conocer los detalles de sus activos de TI, por ejemplo, su configuración y ubicación, es vital para las organizaciones. Los datos recopilados le permiten ver qué procesadores tienen las computadoras en su red, qué sistemas operativos usan los empleados y cuál es el estado actual de sus activos de TI. Esto le brinda información sobre la cantidad de licencias de #[em software] que se han activado y cuáles están a punto de quedar obsoletas. La gestión de equipos informáticos es fundamental para prepararse para la auditoría de licencias de software y garantizar el cumplimiento.
        .cajon.color-acento-botones.p-4(data-aos="fade-left")
          p.mb-0 La importancia del mantenimiento informático garantiza el correcto funcionamiento de los dispositivos y demás elementos internos, observemos este video introductorio al respecto:

    figure.mb-5(data-aos="zoom-in")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/dJ0rNne1xuY" title="Gestión de equipos informáticos" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    
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
