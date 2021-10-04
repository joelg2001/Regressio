# Regressio
Consideraremos que las columnas de refill liters y refill gas no son importantes, ya que el consumo
total ya nos incluira la media de litros por metros consumidos. Con lo cual, no nos estara aportando
informacion a dicho dato. A mas ya tenemos el tipo de gas que utiliza en otra columna.

La columna specials, se ve incluida en otras columnas asi que tambien sera eliminada

Hemos tenido que cambiar los decimales a , para que el pandas lea los valores como integer/float

Los valores en NaN de la columna temp_inside seran substituidos por la media de los valores que
conocemos.
