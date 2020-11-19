# NEXT_TFG

## PROFILE
Incluye la función que hace un profile plot en python. Funciona utilizando la scipy.binned_statistics y los resultados son bastante buenos.

## nS2 & nTr
Análisis de las trazas de cada evento en función de los pulsos S2 que se observan.

## Trazas e Trazas == 0
Un poco de todo. Análisis de longitud de trazas y distribución en energías con el corte **nS2 == 1** (esta parte está aun sin pulir). Después, un análisis aun en proceso de las trazas con longitud 0. Este es el único archivo que aun utiliza el ntuple viejo.

## hits
El último análisis. Incluye la función que analiza los hits de cada traza y los representa en 2 y 3 dimensiones, variando su tamaño en función de su energía. Ofrece tambíen dos vistas: cámara y local
