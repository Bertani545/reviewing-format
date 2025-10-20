# Suma de variables

## Paso 1 @showdialog

Vamos a sumar dos variables y mostrar el resultado


## Creación de variables

Creamos las variables ``||variables:a||`` y ``||variables:b||`` yendo al menú ``||variables:Variables||`` y dando click en **Crear una variable...**



## Cambiando el valor

En ``||basic: on start||`` colocamos  dos bloques ``||variables:set||``. Ambos dicen "set b to 0", así que cambiamos uno de los dos por a y colocamos un valor entre 1 y 10 en lugar de 0.




## Mostando las variables

Ahora creamos dos bloques ``||basic:showString||`` y los colocamos debajo de los que teníamos.
Vamos a  ``||variables:Variables||`` y sustituimos el texto de los bloques por los bloques ``||variables:a||`` y  ``||variables:b||`` 

```blocks
// @validate-exists
let a = 2
let b = 3
basic.showString(a)
basic.showString(b)
```