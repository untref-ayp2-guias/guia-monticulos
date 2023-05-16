# Guía 15

## Desafíos con Montículos

### Parte 0: Implementación de referencia

Ver la carpeta `/src/monticulo` para una implementación de referencia de Montículo de Máximo, junto a sus tests.

#### Ejecutar tests

    % go test ./...

### Parte I: Seguimientos


Dado el siguiente montículo de MÁXIMO (del cual sólo se muestran las prioridades de sus elementos):
```
         [25]
    [15]      [20]
  [6]  [10]
```

1. Ejecutar la siguiente secuencia: Insertar 45, Insertar 22, EliminarMáx, Insertar 5. Realice los dibujos del montículo luego de cada momento (tanto el árbol como el arreglo).

   Puede verificar sus pasos en visualgo.net/en/heap

2. En un montículo de MÍNIMO vacío, ejecutar la secuencia (de la cual sólo conocemos las prioridades de los elementos):

   10, 12, 1, 14, 6, 5, 8, 15, 3, 9, 7, 4, 11, 13, 2. EliminarMín, EliminarMín.


### Parte II: Inserciones Amañadas

Dado un Montículo de MÁXIMO y la siguiente secuencia de inserción (de la cual sólo conocemos las prioridades de los elemntos):
10, 12, 1, 14, 6, 5, 8, 15, 3, 9, 7, 4, 11.

4. Asigneles prioridades tales que al insertarlos en ese orden, sean extraídos en el mismo orden en que fueron ingresados.

5. Asigneles prioridades tales que al insertarlos en ese orden, sean extraídos en orden inverso al que fueron ingresados.


### Parte III: Modificando Montículos

Dado un Montículo de MÁXIMO:

6. Escriba un constructor alternativo `NuevoMonticuloMaxDesdeArreglo` que tome como parámetro un arreglo desordenado de elementos y devuelva un montículo que contenga esos elementos.

7. Escriba una función que, dado un Montículo de tamaño M y un número entero n, con n >= 1 y n <= M,
devuelva el enésimo máximo del montículo. (Ej: si n == 1, devolver el primer máximo.)

8. Escriba una función que, dados dos montículos, devuelva un tercero que sea la combinación de ambos.


### Ejercicios extra

9. Resuelva los puntos anteriores de las Partes II y III para la Montículo de MÍNIMO.