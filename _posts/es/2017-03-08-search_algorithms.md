---
title: "Búsquedas"
lang: es
category: es
permalink: es/search_algorithms

ident: search_algorithms
parent: algorithms
kind: definition
mathjax: false

layout: post
type: post
---

Uno de los problemas básicos es encontrar un elemento guardado en una estructura de datos. La solución a este problema viene dado por un algoritmo de búsqueda.

Los algoritmos de búsqueda son específicos para cada estructura de datos, siendo los más comunes los empleados en las listas de elementos.

Contamos, en este caso, con dos algoritmos diferentes:

- Búsqueda lineal. Recorremos la lista sin repetir los elementos ya visitados hasta llegar a nuestro objetivo, si se consigue encontrar. Se trata de un algoritmo de complejidad lineal aplicable a cualquier tipo de lista.

- Búsqueda binaria: Es un algoritmo para listas ordenadas. Aprovecha esta propiedad específica para obtener una mejora en su complejidad, que es logarítmica.<br/><br/>
La idea consiste en consultar el elemento que se encuentra en la mitad de la lista. Si este elemento es igual al elemento que buscamos, hemos terminado, en otro caso, el elemento medio puede ser mayor o menor. En el primer caso tenemos que nuestro objetivo se encuentra en la primera mitad de la lista, y en el segundo, en la otra mitad (suponiendo un orden de menor a mayor).<br/><br/>
Ahora solo tenemos que buscar en una lista de la mitad de tamaño que la inicial, sobre la que podemos volver a emplear el mismo método. El algoritmo termina cuando se encuentra con el elemento buscado o cuando se le pide hacer una búsqueda en una lista vacia (si el elemento no se encuentra en la lista).
