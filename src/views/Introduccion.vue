<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .row.mb-4
      .col-12
        .px-4.pt-4.pt-xl-0.bg-c1
          .row.align-items-center
            .col-xl-9(data-aos="fade-right")
              p El componente formativo “Ser Individuo” hace parte del programa Ética y Cultura de Paz, y tiene como propósito fundamental fortalecer el desarrollo personal y social desde una perspectiva ética y de convivencia pacífica.
              p En una sociedad marcada por cambios constantes y múltiples desafíos, es esencial que cada persona reflexione sobre su papel en la construcción de relaciones basadas en el respeto, la dignidad y la empatía.
              p.mb-0 Este componente invita a:
            .col-xl-3(data-aos="fade-left")
              figure
                img(src="@/assets/curso/intro/img1.svg", alt="", style="width: 230px").m-auto
    .row.justify-content-center.mb-4
      .col-md-6.col-lg-4.mx-0.mb-4.mb-lg-0(data-aos="fade-right")
        .row
          .col-12
            figure
              img(src="@/assets/curso/intro/img2.png", alt="", style="width: 400px").m-auto
        .row
          .col-12
            .p-4.bg-c2
              p.text-center.mb-0 Comprender la importancia de los derechos humanos como base para una convivencia justa y equitativa.
      .col-md-6.col-lg-4.mx-0.mb-4.mb-lg-0(data-aos="fade-down")
        .row
          .col-12
            figure
              img(src="@/assets/curso/intro/img1.png", alt="", style="width: 400px").m-auto
        .row
          .col-12
            .p-4.bg-c2
              p.text-center.mb-0 Comprender la importancia de los derechos humanos como base para una convivencia justa y equitativa.
      .col-md-6.col-lg-4.mx-0(data-aos="fade-left")
        .row
          .col-12
            figure
              img(src="@/assets/curso/intro/img3.png", alt="", style="width: 400px").m-auto
        .row
          .col-12
            .p-4.bg-c2
              p.text-center.mb-0 Comprender la importancia de los derechos humanos como base para una convivencia justa y equitativa.
    .row.align-items-center
      .col-lg-8.mb-4.mb-lg-0(data-aos="fade-right")
        p También promueve el diseño de un proyecto de vida que:
        ul.lista-ul--color
          li.d-flex
            i.fas.fa-circle-check
            |
            p.mb-0 Se base en el respeto, la dignidad y la empatía.
          li.d-flex
            i.fas.fa-circle-check
            |
            p.mb-0 Incluya metas claras y realistas orientadas al crecimiento personal, profesional y comunitario.
          li.d-flex
            i.fas.fa-circle-check
            |
            p.mb-0 Considere la convivencia y el compromiso con los distintos entornos sociales.
        p.mb-0 A través de este proceso formativo, el individuo se reconoce como protagonista en la transformación de su entorno, actuando con responsabilidad, sentido ético y compromiso con la paz.
      .col-lg-4(data-aos="fade-left")
        figure
          img(src="@/assets/curso/intro/img4.png", alt="", style="width: 400px").m-auto

</template>

<script>
export default {
  name: 'Introduccion',
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
