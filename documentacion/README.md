# Proyecto de ensayo de hormigón

## Propósito

Este proyecto organiza y documenta el procesamiento de datos provenientes de un ensayo de compresión de hormigón. El objetivo es mejorar la trazabilidad del proyecto heredado y permitir comprender la relación entre los datos, el procesamiento y los resultados obtenidos.

## Archivos principales

- `datos/`: contiene los archivos originales recibidos.
- `proceso/`: contiene el archivo utilizado para el análisis.
- `Resultados/`: contiene el gráfico obtenido del procesamiento.
- `Documentacion/`: contiene el informe, las notas y la documentación del proyecto.
## Entradas

Los archivos originales recibidos corresponden a dos planillas Excel:

- `datos/ensayo_hormigon.xlsx`
- `datos/ensayo_hormigon_FINAL_v2.xlsx`

El proyecto heredado también incluye un gráfico, un informe, notas y un archivo relacionado con el uso de IA.

## Procedimiento

1. Se revisaron los archivos originales del proyecto heredado.
2. Se identificaron problemas de organización, trazabilidad y documentación.
3. Se conservó una copia de los archivos originales sin modificarlos.
4. Se utilizó una copia de `ensayo_hormigon_FINAL_v2.xlsx` como archivo de trabajo en `proceso/analisis.xlsx`.
5. Se documentó el cálculo del área utilizada en el procesamiento.
6. Se verificó que el valor de `fmax` coincide con el máximo de la columna de esfuerzo.
7. Se verificó que el gráfico corresponde a los datos procesados.
## Salidas

El procesamiento genera un valor máximo de esfuerzo (`fmax`) de 25,46478899 y un gráfico de desplazamiento versus esfuerzo, almacenado en `resultados/grafico_final.png`.

## Limitaciones y aspectos pendientes

- Las unidades de las variables del proyecto heredado no están especificadas en los archivos recibidos y quedan pendientes de verificación.
- El archivo heredado utiliza el valor 17671,46 como área de cálculo, obtenido a partir de D=150 mediante A = π·D²/4.
- La procedencia y justificación del factor 1000 utilizado en el cálculo de `sigma` debe quedar documentada o verificada antes de considerar cerrado el análisis.
