# PRFILE GENERAL IDEA
Mi idea general para el profile fue coger el eje de las X y subdividirlo en listas más pequeñas (de la longitud que queramos). Una vez tengamos esas sublistas, 
podemos hacer la media de sus valores y usar como nuevo punto en X esa media, de manera que así podemos hacer un Scatter de la media de las Y's frente la media de 
las X's (porque es un scatter normal no podemos representar valores frente a sublistas).

Esto funciona genial si usamos una lista inicial X como x = [1,2,3,4,5,6,7, …] porque están ordenados. Intenté ordenar los elementos de cdf.evt_energy, pero al 
existir valores Nan, esto no funciona, y si quito los Nan, X e Y tienen distinta longitud.
