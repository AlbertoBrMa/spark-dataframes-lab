# Evidencias de la práctica

## 1. Entorno levantado

- Captura de JupyterLab

![JupyterLab](img/entorno_levantado_jupyter.png)

- Captura del Spark Master UI

![Spark Master UI](img/entorno_levantado_spark.png)

## 2. Lectura de datos

- Esquema de `clientes`, esquema de `pedidos` y muestra inicial de datos

![Lectura de datos](img/lectura_datos.png)

## 3. Limpieza

- Resultado tras `trim` y eliminación de duplicados (43 → 40)

![Limpieza - conteo y nulos](img/limpieza.png)

- Tratamiento de valores nulos en pedidos y esquema tras conversión de tipos

![Limpieza - nulos y transformación](img/limpieza2.png)

## 4. Join

- Resultado del join entre clientes y pedidos y explicación de los registros perdidos

![Join](img/join.png)

## 5. Agregaciones

- Ventas Premium con importe >= 100

![Filtrado Premium](img/filtrado.png)

- Clasificación de pedidos con `when` en Alto / Medio / Bajo

![Clasificación when](img/when.png)

- Resumen por ciudad y segmento

![Agregaciones](img/agregaciones.png)

## 6. SQL

- Consulta SQL realizada y resultado obtenido

![SQL](img/sql.png)

## 7. Parquet

- Escritura del resultado y lectura posterior del fichero Parquet

![Parquet](img/parquet.png)

- Muestreo con `sample()` y partición con `randomSplit()`

![Muestreo](img/muestreo.png)
