<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal
      .titulo-principal__numero
        span 5
      h1 Proceso de servicio al cliente en redes sociales

    p.mb-4 Los avances tecnológicos y el comercio electrónico han cambiado la interacción, atención y servicio al cliente, este escenario digital promueve una interacción inmediata a través de portales, sitios web o redes sociales, lo cual genera un proceso. Una vez revise el siguiente recurso educativo tendrá la capacidad de describir el paso a paso de un proceso de servicio al cliente en las redes sociales. 
    p.mb-5 ¡Adelante!

    .tarjeta.tarjeta--gris.p-4.mb-5
      //- LineaTiempoC debe ir acompañado de una de una de estas clases => 
      //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
      LineaTiempoC.color-acento-contenido
        .row(titulo="Paso 1")
          .col-lg-1
          .col-lg-3
            figure
              img(src='@/assets/curso/tema5/img01.svg', alt='Texto que describa la imagen')        
          .col-md-7
            h4 Conformar un equipo.
            p Integrar un equipo para capacitarlo  en relación con la atención en redes. Un elemento a considerarse es humanizar la interacción y el servicio de ellos con el cliente.
          .col-lg-1
        .row(titulo="Paso 2")
          .col-lg-1
          .col-lg-3
            figure
              img(src='@/assets/curso/tema5/img02.svg', alt='Texto que describa la imagen')        
          .col-md-7
            h4 Diseño de guía específica.
            p Planear un documento que dé cuenta del espíritu de la marca y de la empresa. Algunas indicaciones son: tono de voz de la marca, idiomas, tiempo ante cada requerimiento  y el protocolo de resolución de problemas.
          .col-lg-1
        .row(titulo="Paso 3")
          .col-lg-1
          .col-lg-3
            figure
              img(src='@/assets/curso/tema5/img03.svg', alt='Texto que describa la imagen')        
          .col-md-7
            h4 Información clara.
            p Dar claridad de los horarios de atención al cliente y compartir  los correos de contacto o números telefónicos para generar mayor comodidad a los clientes.
          .col-lg-1
        .row(titulo="Paso 4")
          .col-lg-1
          .col-lg-3
            figure
              img(src='@/assets/curso/tema5/img04.svg', alt='Texto que describa la imagen')        
          .col-md-7
            h4 Preguntas frecuentes.
            p Identificar cuáles son las preguntas o reclamaciones comunes, para generar un manual en la Web que remita a los clientes. Esto optimizará  la atención.
          .col-lg-1
        .row(titulo="Paso 5")
          .col-lg-1
          .col-lg-3
            figure
              img(src='@/assets/curso/tema5/img05.svg', alt='Texto que describa la imagen')        
          .col-md-7
            h4 Anticiparse.
            p Prever cuáles serán las dudas, preguntas ante su producto y servicio, por eso es necesario crear contenido  exclusivo que pueda tener en sus redes, no esperar  a tener problemas.    
          .col-lg-1
        .row(titulo="Paso 6")
          .col-lg-1
          .col-lg-3
            figure
              img(src='@/assets/curso/tema5/img06.svg', alt='Texto que describa la imagen')        
          .col-md-7
            h4 Seguimiento.
            p Implementar una base de datos de los clientes, para resolver y gestionar la solicitud, volverse a contactar para medir el grado de satisfacción o no con la respuesta ofrecida, esto ayuda a la fidelización de los clientes.
          .col-lg-1
        .row(titulo="Paso 7")
          .col-lg-1
          .col-lg-3
            figure
              img(src='@/assets/curso/tema5/img07.svg', alt='Texto que describa la imagen')        
          .col-md-7
            h4 Medición.
            p Evaluar el impacto de las acciones emprendidas en las redes, esto permitirá visionar,  validar o reestructurar la estrategia de atención al cliente en redes.
          .col-lg-1           
              


</template>

<script>
export default {
  name: 'Tema5',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>
