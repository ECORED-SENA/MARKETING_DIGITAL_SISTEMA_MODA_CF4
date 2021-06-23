<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal
      .titulo-principal__numero
        span 4
      h1 Nuevas tendencias en servicio al cliente en redes sociales
    
    p.mb-4 Hoy en día, los desarrollos en la tecnología y la evolución del marketing al escenario digital han generado nuevos esquemas de relación, interacción y atención al cliente; la Web posibilita nuevas maneras de interactuar con ellos, pues los consumidores se convierten en protagonistas, con varias opciones de interacción; comparten información (foros, chats), premian o castigan contenidos de las diferentes empresas (marcadores sociales), generan opinión (blogs) producen información (wikis, redes sociales). 

    .cajon.color-acento-contenido.p-5.mb-4
      p.text-center.m-0 Este nuevo perfil de cliente crea retos para desarrollar relaciones estrechas entre usuarios, marcas y empresas. Observe el siguiente recurso de aprendizaje para que pueda aplicar algunas tendencias en su contexto laboral.

    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)     


</template>

<script>
export default {
  name: 'Tema4',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>
