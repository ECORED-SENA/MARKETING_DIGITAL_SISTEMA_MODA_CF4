<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal
      .titulo-principal__numero
        span 7
      h1 Normativa legal vigente y ética en el manejo de datos (protección de datos)

    p.mb-4 La normativa de protección de datos personales reconoce y protege el derecho de las personas a conocer, rectificar y actualizar su información almacenada en base de datos o archivos que sean susceptibles de tratamiento por parte de entidades privadas o públicas. En Colombia rige la siguiente normativa.

    .row.mb-5
      .col-lg-9
        TabsA.color-acento-contenido.mb-5   
          .tarjeta.fondo-color-primario-claro2.p-4(titulo="Constitución Política de Colombia")
            p.mb-4 Con respecto al manejo de los datos, la Constitución, en el <b>Artículo 15</b> menciona que todas las personas tienen derecho a su intimidad personal y familiar y a su buen nombre, y el Estado debe respetarlos y hacerlos respetar. De igual modo, tienen derecho a conocer, actualizar y rectificar las informaciones que se hayan recogido sobre ellas en bancos de datos y en archivos de entidades públicas y privadas. 
            p En la recolección, tratamiento y circulación de datos se respetarán la libertad y demás garantías consagradas en la Constitución.
          .tarjeta.fondo-color-primario-claro2.p-4(titulo="Ley 1266 del 2008")
            p En el marco de esta ley  se dictan las disposiciones generales del hábeas data, regulando el manejo de la información contenida en bases de datos personales, en especial la financiera, crediticia, comercial y de servicios. En los <b>Artículos 2 y 4</b> se definen las normas especiales para la confidencialidad de los datos y los principios administrativos de estos. 
          .tarjeta.fondo-color-primario-claro2.p-4(titulo="La Ley 1581 de 2012 ")
            p.mb-4 Esta ley  establece los lineamientos para la protección de datos y la autorización de los titulares para el tratamiento de estos y, define  que datos personales  son cualquier tipo de información asociada a una o varias personas naturales, determinables, como el nombre, la edad, el sexo, el estado civil, el domicilio, entre otros. Además, define que hay diferentes tipos de datos:
            ul.lista-ul
              li 
                i.lista-ul__vineta
                | Dato privado. 
              li 
                i.lista-ul__vineta
                | Dato semiprivado.
              li 
                i.lista-ul__vineta
                | Dato público.
          .tarjeta.fondo-color-primario-claro2.p-4(titulo="Decreto 1377 de 2013")
            p Por el cual se reglamenta parcialmente la Ley 1581 de 2013, en la que se comunica a través de los artículos 4, 11 y 23 la recolección de datos personales que pueden limitarse y su duración en el tiempo.  Finalmente, se establecen los medios para la protección de datos personales. 
      .col-lg-3
        figure.mb-4
          img(src='@/assets/curso/tema7/img01.svg', alt='')

    p.mb-4 Se ha finalizado esta experiencia de aprendizaje relacionada con el servicio y atención al cliente en las redes sociales, se espera que los conocimientos, habilidades y actitudes que desarrolló tengan sentido en la solución de problemas y transformación de procesos en su contexto laboral. 

    figure.mb-4
      img(src='@/assets/curso/tema7/img02.png', alt='')
 
</template>

<script>
export default {
  name: 'Tema7',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>
