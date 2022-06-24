<template>
  <div class="home">
    <h1>Ejercicio 2</h1>
    <p>
      extension: 
      -99.26562067928639,
      19.27666556862522,
      -98.97757289974852,
      19.42405297404042
    </p>

    <p>
      capa xyz: http://tile.stamen.com/watercolor/{z}/{x}/{y}.jpg
    </p>
    <dai-mapa :extension="[-99.26562067928639,19.27666556862522,-98.97757289974852,19.42405297404042]">
      <dai-capa-xyz 
        url="http://tile.stamen.com/watercolor/{z}/{x}/{y}.jpg"
      />
  </dai-mapa>
  </div>
</template>

<script>


export default {
}   
</script>
