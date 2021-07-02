<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    figure.mb-4 
      img(src='@/assets/curso/img01.png', alt='Texto que describa la imagen')

    p.mb-4 Pensar en el servicio y atención al cliente nos acerca a todo lo que pasa con el consumidor durante su decisión de adquirir un bien o servicio. Todo no debe percibirse como una simple acción transaccional, sino que involucra una experiencia que haga sentir la compra como una buena decisión. 
    p.mb-4 En este sentido, el presente componente realizará un recorrido por los fundamentos básicos del servicio y atención al cliente con la intención de que pueda reconocer el estilo de comunicación asociado al servicio al cliente en redes sociales, de acuerdo con las políticas de la empresa. Por tanto, le sugiero observar el siguiente recurso educativo para que conozca las condiciones a considerar para su formación.     
    
    
   

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped>
.introduccion
</style>
