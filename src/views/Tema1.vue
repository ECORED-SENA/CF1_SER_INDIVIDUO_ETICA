<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 Dignidad como fundamento de la cultura humana
    p.mb-0 La convivencia como sociedad ha dispuesto un orden y normas que permitan una sana convivencia mundial.
    Separador
    #t_1_1
    .titulo-segundo.color-primario
      h2 1.1 Concepto
    p La definición del concepto de dignidad humana tiene #[b diferentes #[i perspectivas]] de análisis que incluyen versiones mediadas por el tiempo o época y punto de vista que puede ser filosófico, religioso, social, humanista o jurídico.
    p Veamos algunas definiciones a continuación:
    .row.bg-c3
      .col-12
        .p-5
          .tarjeta.tarjeta--azul1.p-4
            SlyderA(tipo="b")
              .row.justify-content-center.align-items-center.my-lg-4
                .col-md-5.mb-4.mb-md-0
                  p #[b Calienta tu cerebro]
                  p.mb-0 Inicia el día con actividades que despierten tu mente y que a la vez la reconforten. Puedes hacer ejercicios, escuchar música o meditar.
                .col-md-5
                  figure
                    img(src='@/assets/curso/tema1/img2.png', alt='', style="width: 450px").m-auto
              .row.justify-content-center.align-items-center.my-lg-4
                .col-md-5.mb-4.mb-md-0
                  p #[b Calienta tu cerebro]
                  p.mb-0 Inicia el día con actividades que despierten tu mente y que a la vez la reconforten. Puedes hacer ejercicios, escuchar música o meditar.
                .col-md-5
                  figure
                    img(src='@/assets/curso/tema1/img2.png', alt='', style="width: 450px").m-auto
              .row.justify-content-center.align-items-center.my-lg-4
                .col-md-5.mb-4.mb-md-0
                  p #[b Calienta tu cerebro]
                  p.mb-0 Inicia el día con actividades que despierten tu mente y que a la vez la reconforten. Puedes hacer ejercicios, escuchar música o meditar.
                .col-md-5
                  figure
                    img(src='@/assets/curso/tema1/img2.png', alt='', style="width: 450px").m-auto
    Separador
    p #[b Calienta tu cerebro]
    .row
      .col-12.order-2.order-lg-1
        figure.mb-0.mb-lg-4
          img(src='@/assets/curso/tema1/img2.png', alt='', style="width: 450px").m-auto
      .col-12.order-1.order-lg-2
        p.mb-lg-0 Inicia el día con actividades que despierten tu mente y que a la vez la reconforten. Puedes hacer ejercicios, escuchar música o meditar.
    Separador
    .row.bg-c3
      .col-12
        .px-5
          figure
            .video
              iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
          Separador
          SlyderF(columnas="col-md-6 col-xl-4")
            .tarjeta.color-acento-botones1.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/tema1/img2.svg' alt='AvatarTop')
              h2.text-center FIRST
              p.text-center moment. Abandon the shelter of insecurity. Be bold. Greatness isn’t the height of your stature, it’s the heft of your spirit.
            .tarjeta.color-acento-botones1.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/tema1/img2.svg' alt='AvatarTop')
              h2.text-center FIRST
              p.text-center moment. Abandon the shelter of insecurity. Be bold. Greatness isn’t the height of your stature, it’s the heft of your spirit.
            .tarjeta.color-acento-botones1.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/tema1/img2.svg' alt='AvatarTop')
              h2.text-center FIRST
              p.text-center moment. Abandon the shelter of insecurity. Be bold. Greatness isn’t the height of your stature, it’s the heft of your spirit.
            .tarjeta.color-acento-botones1.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/tema1/img2.svg' alt='AvatarTop')
              h2.text-center FIRST
              p.text-center moment. Abandon the shelter of insecurity. Be bold. Greatness isn’t the height of your stature, it’s the heft of your spirit.
    Separador
    .bg--gradientBlue.px-5.mb-4
      SlyderB(:datos="datosSlyderEjemplo")
 
</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({
    mostrarIndicadorTarjetaAudio: true,
    datosSlyderEjemplo: [
      {
        titulo: 'Histograma',
        texto:
          'Agrupación de datos.<br>Sirve para datos <b>cualitativos y cuantitativos</b>.<br>Las barras siempre van unidas.<br>Los histogramas ayudan a ver el centro, la extensión y la forma de un conjunto de datos.',
        imagen: require('@/assets/curso/tema1/img2.png'),
        leyendaImagen: 'Prueba',
      },
      {
        titulo: 'Polígono de frecuencia',
        texto:
          'Gráfico que se crea a partir de un histograma de frecuencia. Estos histogramas emplean columnas verticales para reflejar frecuencias: el polígono de frecuencia es realizado uniendo los puntos de mayor altura de estas columnas.',
        imagen: require('@/assets/curso/tema1/img2.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Diagrama de barras',
        texto:
          'Un diagrama de barras es una representación en dos dimensiones de la frecuencia, ya sea absoluta o relativa, de una variable cuantitativa o cualitativa, pero siempre discreta y distribuida en filas.',
        imagen: require('@/assets/curso/tema1/img2.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Circular',
        texto:
          'Se utiliza para representar la proporción de elementos de cada uno de los valores de la variable.',
        imagen: require('@/assets/curso/tema1/img2.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
    ],
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
