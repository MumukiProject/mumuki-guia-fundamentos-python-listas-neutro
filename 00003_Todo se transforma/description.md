Las listas son muy útiles para contener múltiples elementos. ¡Pero hay más! También podemos agregarle elementos en cualquier momento, utilizando la función `list.append`, que recibe dos parámetros: la lista y el elemento. Por ejemplo:

```python
ム discos = ["Serú Girán", "Artaud", "Almendra", "Quebrado"]
ム len(pertenencias)
4
ム list.append(pertenencias, "Vida")
ム len(pertenencias)
5
```

Como vemos, `list.append` agrega un elemento a la lista, lo cual hace que su tamaño aumente. ¿Pero en qué parte de la lista lo agrega? ¿Al principio? ¿Al final? ¿En el medio? :thinking:

> Averígualo tú: inspecciona en la consola qué elementos contiene `libros`, agrégale `"Fundación"` y vuelve a inspeccionar `libros`.
>
> Además existe una función `list.remove`, que recibe por parámetro una lista y un elemento de ella. Investiga en la consola qué hace. :eyes:
>
>Cuando termines, escribe `listo()`.