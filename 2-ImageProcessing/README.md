# Detección de copas a través de técnicas no supervisadas y procesamiento digital de imágenes.

Flujo de procesamiento digital de imágenes y clasificación no supervisada para detectar cobertura de copas.

![](./images/flow-tree-crown-map.png) 


## Preprocesamiento

 - Filtro de blur gaussiano. [Link](https://en.wikipedia.org/wiki/Gaussian_blur)
 - Escatado con Z-score z = (x – μ)/σ
 
## OTSU
 - Segmentación basada en umbrales de saturación.
 - Trabaja en escala de grises (1 sola banda)
 
## Clustering k-Means

 - Dentro de la máscara de OTSU aplicamos el agrupamiento

## Delineado de copas paso a paso

 ![](./images/step-by-step.png) 
 