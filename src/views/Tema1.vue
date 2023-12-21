<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido
        .titulo-principal__numero
          span 1
        h1 Texto argumentativo    
  
      .row
        .col-xl-12
      #t_1_1.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
        h2.my-5 1.1 Definición
      .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
        .bloque-texto-g__img(
          :style="{'background-image':`url(${require('@/assets/curso/temas/tema1/img1.jpg')})`}"
        )
        .bloque-texto-g__texto.p-4        
          p Un texto argumentativo es una organización textual centrada en el juicio y en la toma de una postura respecto de algún asunto polémico. Dicha acción implica que se defenderá la posición que se asuma a través de una serie de razones. Es por ello que este tipo de escrito tiene como objetivo expresar opiniones o rebatirlas con el fin de persuadir o convencer a un receptor. (Rosado, 2012)
          br
          br
          p Este tipo de texto requiere que el aprendiz investigue un tema; recopile, generé y evalué evidencias; y establezca una posición sobre el tema de manera concisa.

      Separador
      .row
        .col-xl-12
      #t_1_2.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
        h2.my-5 1.2 Formato para elaborar el texto argumentativo
      .row.justify-content-center.align-items-center.mb-5
        .col-lg-12
          p Se propone utilizar el siguiente formato para elaborar el texto argumentativo.
      .row.justify-content-center.align-items-center
        .col-lg-10.col-md-4.mb-md-0(data-aos="flip-left")
          .titulo-sexto.color-acento-contenido.offset-0
            h5 Figura 1.
            span  #[i  Texto argumentativo]
      .row.justify-content-center.align-items-center.mb-5
        .col-lg-10.desktop(data-aos="flip-up")
          figure
            img(src='@/assets/curso/temas/tema1/img2.svg', alt='En la figura se tiene un diagrama de flujo, iniciando en la parte superior con el texto argumentativo, en el nivel inferior se tiene la estructura de un texto argumentativo, y en el nivel inferior se tiene la tesis, los argumentos y las conclusiones.')          
        .col-lg-12.movil
          figure
            img(src='@/assets/curso/temas/tema1/img2_1.svg', alt='En la figura se tiene un diagrama de flujo, iniciando en la parte superior con el texto argumentativo, en el nivel inferior se tiene la estructura de un texto argumentativo, y en el nivel inferior se tiene la tesis, los argumentos y las conclusiones.')
      
      .row.justify-content-center.align-items-center.mb-5
        .col-lg-12
          p #[b La tesis]:  es un párrafo introductorio que presente el argumento y explica la idea que va defender.
          p #[b Los argumentos]: en este espacio se presentan las ideas que respaldan su tesis, y se explica por qué está de acuerdo con ella.
          p #[b Conclusiones]: es la parte final del texto. En ella se ratifica la tesis, se resumen los argumentos, se hace un pedido, un llamado de atención.
      Separador
      .row
        .col-xl-12
      #t_1_3.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
        h2.my-5 1.3 Pasos para elaborar la práctica
    
      .row.justify-content-center.align-items-center
        .col-lg-10.col-md-4.mb-md-0(data-aos="flip-left")
          .titulo-sexto.color-acento-contenido.offset-0
            h5 Figura 2.
            span  #[i  Características de un texto argumentantivo]
      .row.justify-content-center.align-items-center.mb-5
        .col-lg-10.desktop(data-aos="flip-up")
          figure.mb-3
            img(src='@/assets/curso/temas/tema1/img3.svg', alt='En la figura se representa en la parte superior el título con autores y productores, luego en un nivel inferior se tiene la temática y posteiormente los objetivos, sigue la figura llendo de lo general con la introducción a lo particular con la tesis. Y en la parte inferior se va de lo particular con los argumentos a lo general con las conclusiones.')          
          figure
            img(src='@/assets/curso/temas/tema1/img3_1.svg', alt='En la figura se representa en la parte superior el título con autores y productores, luego en un nivel inferior se tiene la temática y posteiormente los objetivos, sigue la figura llendo de lo general con la introducción a lo particular con la tesis. Y en la parte inferior se va de lo particular con los argumentos a lo general con las conclusiones.')          
          figcaption Nota: Adaptado de Centro de Escritura Javeriano. (s.f). Cómo escribir un ensayo y no morir en el intento.
        .col-lg-12.movil
          figure.mb-3
            img(src='@/assets/curso/temas/tema1/img4.svg', alt='En la figura se representa en la parte superior el título con autores y productores, luego en un nivel inferior se tiene la temática y posteiormente los objetivos, sigue la figura llendo de lo general con la introducción a lo particular con la tesis. Y en la parte inferior se va de lo particular con los argumentos a lo general con las conclusiones.')
          figure
            img(src='@/assets/curso/temas/tema1/img4_1.svg', alt='En la figura se representa en la parte superior el título con autores y productores, luego en un nivel inferior se tiene la temática y posteiormente los objetivos, sigue la figura llendo de lo general con la introducción a lo particular con la tesis. Y en la parte inferior se va de lo particular con los argumentos a lo general con las conclusiones.')
          figcaption Nota: Adaptado de Centro de Escritura Javeriano. (s.f). Cómo escribir un ensayo y no morir en el intento.

      
      Separador
      .row
        .col-xl-12
      #t_1_4.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
        h2.my-5 1.4 Pasos para elaborar un texto argumentativo
  
      .row.justify-content-center.align-items-center.mb-5
        .col-lg-4.col-md-6.col-sm-4
          figure
            img(src='@/assets/curso/temas/tema1/img5.svg', alt='Imagen decorativa')
        .col-lg-8
          ol.lista-ol--cuadro
            li
            .lista-ol--cuadro__vineta
              span 1
            | Registrar el siguiente título establecido como tema principal para el texto.
            li
            .lista-ol--cuadro__vineta
              span 2
            | Describir la introducción con información pertinente y contextualizada según el tema a abordar. En un párrafo de seis renglones.
            li
            .lista-ol--cuadro__vineta
              span 3
            | Registrar la tesis: hay quienes afirman que no es importante para la construcción de ítems e indicadores aplicar la estructura establecida en la metodología.
            li
            .lista-ol--cuadro__vineta
              span 4
            | Realizar el desarrollo de tres argumentos o contra argumentos de acuerdo a la tesis propuesta.
            li          
            .lista-ol--cuadro__vineta
              span 5
            | Definir lo que se puede lograr, cuáles son los argumentos que se utilizan para persuadir al espectador y cuál será el orden de los argumentos. Se pueden ordenar los argumentos por su fuerza: empezar con el argumento más fuerte y terminar con el más débil, o viceversa.  También, pueden ser agrupados por temas o autores.
            li          
            .lista-ol--cuadro__vineta
              span 6
            | Registrar las conclusiones después del análisis, las cuales reiteran o contravienen la tesis.                      
            li
            .lista-ol--cuadro__vineta
              span 7
            | Realizar una revisión final de la gramática, redacción y ortografía del texto.
  
  
    
      Separador
      .row
        .col-xl-12
      #t_1_5.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
        h2.my-5 1.5 Herramientas digitales que se pueden utilizar para la elaboración de texto argumentativo
      .row.justify-content-center.align-items-center.mb-5
        .col-lg-4
          .tarjeta-avatar
            img(src='@/assets/curso/temas/tema1/img6.svg' alt='AvatarTop')
            .tarjeta.color-primario.w-100
              .p-4
                h4.text-center.text-black #[i(style="color:#000000;") Word]
                p.text-center(style="color:#000000;") El procesador de texto del paquete Office de Microsoft, es el más usado y tal vez potente en el medio, puede usarse como aplicación nativa o en línea, para escribir textos. 
        .col-lg-4
          .tarjeta-avatar
            img(src='@/assets/curso/temas/tema1/img7.svg' alt='AvatarTop')
            .tarjeta.color-primario.w-100
              .p-4.mb-3
                h4.text-center.text-black Corrector #[i(style="color:#000000;") Online]
                p.text-center(style="color:#000000;") Revisión y mejora de gramática de textos
                a.anexo.mb-4.mb-lg-0(href="https://www.correctoronline.es/" target="_blank")
                  .anexo__icono
                    img(src="@/assets/template/icono-link.svg")
                  .anexo__texto
                    p(style="color:#000000;") https://www.correctoronline.es/
        .col-lg-4
          .tarjeta-avatar
            img(src='@/assets/curso/temas/tema1/img8.svg' alt='AvatarTop')
            .tarjeta.color-primario.w-100
              .p-4.mb-3
                h4.text-center #[i(style="color:#000000;") Language Tool]
                p.text-center(style="color:#000000;") Revisión de ortografía y estilo. 
                a.anexo.mb-4.mb-lg-0(href="https://languagetool.org/es" target="_blank")
                  .anexo__icono
                    img(src="@/assets/template/icono-link.svg")
                  .anexo__texto
                    p(style="color:#000000;") https://languagetool.org/es
  
  </template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
