<template>
  <div class="home">
    <h1>Ejercicio 1</h1>
    <p>Agregando un mapa con una capa</p>
    <dai-mapa :extension="[-101.2,18.3,-98.0,20.3]">
      <dai-capa-xyz-osm/>
      <dai-capa-geojson
          url="./movilidad_mun_2010_edos15_09.geojson"
          :reglas-estilo-capa="{
              clasificacion:'cuantiles',
              columna:'porc_n_mov',
              colores:'Blues'
          }"
          :contenido-tooltip="f=>`<b>Clave</b> ${f.cvegeo}`"
      />
    </dai-mapa>
  </div>
</template>

<script>


export default {
}   
</script>
