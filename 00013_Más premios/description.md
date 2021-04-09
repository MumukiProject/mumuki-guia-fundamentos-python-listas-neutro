Como hemos visto, al pedir un elemento en una posición igual o mayor al tamaño de la lista, se producirá un error `IndexError: list index out of range`. Así que ¡cuidado, no te pases de índice! :warning:

> Teniendo esto en cuenta, va un desafío: define nuevamente la función `medalla_segun_puesto`, pero esta vez usando como máximo un único `if`. Quizás las listas te pueden ser útiles aquí :wink:.
>
> Te recordamos qué hace la función: tiene que devolver la medalla que le corresponde a los primeros puestos de una competencia.
>
>```python
>ム medalla_segun_puesto(1)
>"oro"
>ム medalla_segun_puesto(2)
>"plata"
>ム medalla_segun_puesto(3)
>"bronce"
>ム medalla_segun_puesto(4)
>"nada"
>ム medalla_segun_puesto(5)
>"nada" 
```
